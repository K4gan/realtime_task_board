# Realtime Task Board

    In-memory task board with event stream primitives.

    ## Stack

    - Language: TypeScript
    - Difficulty: high
    - Scope: small, self-contained service/tool with clear extension points

    ## Project layout

    The repository keeps implementation code under `src/` where that is idiomatic, plus a short runnable entry point and a small sample payload when useful.

    ## Run

    ```bash
    npm install
npm run build
npm start
    ```

    ## Engineering notes

    The implementation keeps parsing, domain logic and output formatting separate enough to grow without turning into a script dump. Generated artifacts and dependency folders are intentionally ignored.
