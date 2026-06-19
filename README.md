**Hyades - Active attitude control system**

Bare-metal GNC flight software for a fin-actuated, actively attitude-controlled high-power rocket. Single-board STM32H7 flight computer, full guidance–navigation–control stack, designed for deterministic real-time execution and host-side verification.

What this is

A from-scratch, real-time GNC stack for an actively stabilised high-power rocket. The vehicle uses canard/strake control surfaces driven by an STM32H743 primary flight computer reading an ICM-42688-P IMU, with a complete software pipeline from raw inertial samples to fin commands and pyrotechnic recovery sequencing.

The project is developed in the open as an engineering record. Design decisions, trade studies, and test methodology are documented alongside the code rather than after it.

This is a learning and engineering project, not a product. Code fragments in the documentation are illustrative skeletons; the safety case, regulatory compliance, and airworthiness of any vehicle built from this material are the builder's sole responsibility.
