# nestjspractice
        
 
Req or Res <-> Server:
- Validate data and contained in the request [Pipe]
- Make sure the user is authenticated [Guard]
- Route the reuest to a particular function [Controller]
- Run some business logic [Service]
- Access a database [Repository]

Parts of Nest:
1. Controllers - Handles incoming requests
2. Services - Handles data access and business logic
3. Modules - Groups together code
4. Pipes - Validates incoming data
5. Filters - Handles errors that occur during request handling
6. Guards - handles authentication
7. Interceptors - Adds extra logic to incoming requests or outgoing responses
8. Repositories - Handles data stored in DB
