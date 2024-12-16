The API Layer is the entry point for external interactions with the application. It exposes the application’s functionality via RESTful APIs or minimal APIs.

## Key Responsibilities:
1. Handle **Requests**:
   - Receive HTTP requests from clients (frontend, external systems).
2. Use **Application Services**:
   - Delegate tasks to the Application Layer to perform business logic (which can be found in services).
3. Return **Responses**:
   - Format and return appropriate responses (e.g., HTTP status codes, JSON objects).

