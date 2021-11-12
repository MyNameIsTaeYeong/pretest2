# Process Management

- 프로세스란?
- 스레드란?
- 프로세스의 구성요소 및 역할
- CPU 스케쥴링
  - PCB
  - Context Switching
  - Interrupt
  - Deadlock
  - Race condition
  - Semaphore
  - Mutex
  - FCFS
  - SJF
  - SRTF
  - Priority Scheduling
  - RR

# Memory Management

- frame
- page
- segment
- Virtual Memory
  - 모든 메모리 참조는 실행중에 논리주소에서 물리주소로 변환된다. (MMU의 도움을 받는다.)
  - 프로세스는 메모리에 연속적으로 위치할 필요가 없다.
- Paging(물리단위)
- Segmentation(논리단위)
- Replacement Policy
  - Optimal
  - LRU(Least recently used)
  - FIFO
  - Clock
