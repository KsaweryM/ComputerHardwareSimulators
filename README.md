# Computer Hardware simulators

Interactive simulators for the [Computer Hardware Course](https://github.com/KsaweryM/Computer-Hardware-Course), collected on one page.
Pick a lecture and a topic in the sidebar; the page works in Polish and English.

| Lecture | Simulator |
|---------|-----------|
| 3 | RISC-V pipeline: stalls, forwarding and flushes |
| 4 | Direct-mapped cache |
| 5 | Input/output: I2C, device registers, the GPIO controller, polling, interrupts, DMA |
| 6 | Interrupts and the scheduler: polling, the timer tick, time slices, the context switch, task states |
| 7 | Threads: the race, the mutex |
| 8 | Deadlock and the producer-consumer problem |

Everything runs in the browser, nothing to install. Open `index.html`, or publish the repository with GitHub Pages.

## Structure

- `index.html`: the page with the sidebar
- `sims/<name>/index.html`: the simulators; the page loads them with `?embed=1&lang=pl|en`, which hides their own header and topic picker

Each simulator also works on its own: open `sims/<name>/index.html` directly.
