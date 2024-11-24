```mermaid

sequenceDiagram

    title exercise 0.6 jonatan
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: [{ "content": "Hello from Spain", "date": "2024-11-24" }, ... ]
    deactivate server
```