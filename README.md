# MerdOS

## Symulacja systemu operacyjnego napisana w Javie jako projekt studencki ##

Na symulację składają się:
- Planista niskopoziomowy przydzielający czas procesora. Wykorzystano planowanie priorytetowe oraz rotacyjne. Każdemu z procesów przydzielany jest kwant czasu procesora na podstawie jego priorytetu.
- Procesy w formie drzewa z procesem systemowym jako ich korzeniem (rozwiązanie zbliżone do systemów Linux) wraz z PCB (Blokami kontrolnymi procesów).
- System plików oparty o i-węzły.
- Pamięć RAM o bardzo małej pojemności (w celu wymuszenia wykorzystania pamięci wirtualnej).
- Pamięć wirtualna z algorytmem drugiej szansy.
- Semafory w celu synchronizacji.
- Interpreter rozkazów procesów.
- Interfejs tekstowy.

## Operating system simulation written in Java as part of University project ##

Simulation consists of:
- Low-level planner assigning CPU time. Planner combines priority scheduling and round-robin scheduling. Slices of CPU time are assigned based on process priority.
- Processes in tree architecture with system process as root (similar to Linux systems) and PCBs.
- File system based on i-nodes.
- Low capacity RAM (in order to force the usage of virtual memory).
- Virtual memory with second chance page replacement algorithm.
- Synchronization based on semafors.
- Process command interpreter
- Text-based interface.
