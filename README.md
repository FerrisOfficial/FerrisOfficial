# Maciej Stempniak

**Backend & Systems Engineer — C++ and .NET**

I build production backend and systems software across C++, C#/.NET and Python. I currently work on KSeF backend services at Symfonia; previously, I shipped C++20 features for Nokia's 5G RAN software.

Based in Warsaw, Poland. EU citizen, open to relocation across the EU.

## Experience

**Symfonia — .NET Backend Developer**  
Developing and debugging C#/.NET backend services and GraphQL APIs for Poland's national e-invoicing platform. My work includes KSeF API integration, SQL persistence, automated tests, production investigation and policy-enforced workflows using technologies including Hangfire, Dapr, Kubernetes and OPA.

**Nokia — C++ Software Engineering, 5G RAN**  
Joined as a summer trainee and was selected to continue with the team on a contract. Developed and validated C++20 decision logic for temperature-aware cell activation, traffic control and energy management in 5G base stations, using Linux, Clang, GDB, Valgrind, Git and Gerrit.

## Selected work

### [Two-Player Catan Research Engine & AI](https://github.com/FerrisOfficial/CatanAPI)

A co-authored C++20 research engine for reproducible two-player Catan tournaments and game-AI experiments.

- Bit-packed fixed board state under 800 bytes, with apply/undo transitions instead of complete-board copies
- 250–300 random-vs-random games per second in a representative native Clang 22 `-O3` build
- 242 generated test cases across six binaries, with GCC, MSVC, Clang and AddressSanitizer CI
- 13 native agents spanning deterministic heuristics, chance-aware alpha-beta and evolutionarily tuned evaluation
- [Live WebAssembly demo](https://maciejstempniak.com/#catan-demo) and [engineering notes](https://github.com/FerrisOfficial/CatanAPI#why-the-engine-matters-more-than-the-agents)

### [Bot Arena](https://github.com/BartoszKruszewski/bot-arena)

A co-developed Python environment for programming-game tournaments. I implemented the game logic, map generation, bot interface and packaging, process timeout enforcement, structured match logs and move-by-move replay.

### [SpaceX Launch Data API](https://github.com/FerrisOfficial/dotnet-public-api-weaver)

A compact .NET 10 Minimal API demonstrating idempotent external-data imports, EF Core/SQLite persistence, bounded parameters, cancellation propagation and automated unit and end-to-end tests.

## Core toolkit

- **Languages:** C++20, C#/.NET, Python
- **Backend:** GraphQL, REST APIs, SQL, EF Core, Hangfire, Dapr, OPA
- **Systems and delivery:** Linux, CMake, GDB, Valgrind, Docker, Kubernetes, CI
- **Testing:** GoogleTest, xUnit, pytest, sanitizers and multi-compiler builds

## Background

B.Eng. in Computer Science from the University of Wrocław. My bachelor thesis focused on the Catan research engine above and received a grade of 5/5.

## Contact

[Portfolio](https://maciejstempniak.com) · [LinkedIn](https://www.linkedin.com/in/stempniak-maciej/) · [Email](mailto:maciek.m.stempniak@gmail.com)
