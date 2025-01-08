![stateless and stateful](https://github.com/user-attachments/assets/45c7079b-92f6-464b-90be-8706c329d880)

The primary issue with traditional hashing methods :-

When a node is added or removed, most of the keys need to be rehashed and redistributed.  
If Let Suppose :-  
There are 3 Nodes  
Shreyansh is came to Load Balancer as id  
According to hash method it saved in Node 2  
Now One More Node Added  
Now h(Shreyansh)%4 will give different Node , say Node 3  
But our data is saved in Node 2.  

![cascading failure](https://github.com/user-attachments/assets/9a437285-db7e-4829-ba98-045419c2bd4e)

![consistent hashing](https://github.com/user-attachments/assets/0327eb44-de8a-4d70-8139-c66226e404a0)
