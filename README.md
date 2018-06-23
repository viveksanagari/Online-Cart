# Online-Cart

Online-cart is an application where user can shop online and save the items to his cart for later purchase. Here the list of items added to the cart by the user is his state in the application. 

Additional Information:
This state is saved to a file on the block storage device which is replicated (Using Distributed Replicated Block Storage) among the servers of the service provider. Thus, ensuring that the service is provided to user without interruption, by one of the servers. The idea is to save the user actions on the application (Here, list of items added by the user). This idea can be generalized to other complex applications such as online text editor where the text edited by the user can be saved to the block storage device, replicated among the servers. Thus, the text of the user can be retrieved without any service interruption.
