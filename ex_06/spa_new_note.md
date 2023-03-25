<div class="mermaid">
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/spa
    activate server
    server-->>browser: 201 note created
    deactivate server 

    Note right of browser: Payload accompanying the request is in json format. Status code 201, note created response.
</div>
