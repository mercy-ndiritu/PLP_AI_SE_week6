Part 1: Theoretical analysis
Edge AI vs. cloud-based AI
Latency reduction: Processing on-device eliminates round-trip network delays. In time-sensitive tasks, even 100–300 ms of network latency can cause failures, whereas local inference often runs in tens of milliseconds, depending on hardware and model size.
Privacy enhancement: Sensitive data (images, voice, biosignals) stays on the device; only derived or aggregated results are sent upstream, reducing exposure risk and regulatory overhead.
Bandwidth efficiency: Continuous sensor streams are compressed into decisions locally, making systems viable in low-connectivity environments.
Resilience: Local inference works offline, crucial for safety-critical or remote deployments.

Real-world example (autonomous drones):

Onboard vision model: Detects obstacles and landing zones locally.
Outcome: Faster path planning, safe navigation without network reliance.
Privacy: No raw video uplink needed; only mission telemetry is transmitted.
Bonus: Extends battery life by avoiding constant radio transmission.

Quantum AI vs. classical AI for optimization
Classical AI/OR: Uses heuristics, gradient methods, mixed-integer programming, and metaheuristics for problems like routing, scheduling, and portfolio optimization.

Quantum AI (and quantum-inspired):

Quadratic unconstrained binary optimization (QUBO): Encodes combinatorial problems suited for quantum annealing.
Variational quantum algorithms (VQAs): Hybrid quantum-classical loops that search solution spaces differently than gradient-only classical methods.
Potential advantage: Exploring complex energy landscapes more efficiently for certain structures; still early-stage and hardware-limited.

Industries likely to benefit most:

Logistics & transportation: Vehicle routing, hub placement, timetabling.
Finance: Portfolio optimization, risk parity, market making.
Manufacturing: Job-shop scheduling, supply chain resilience.
Energy: Grid optimization, unit commitment, battery dispatch.
Telecom: Network traffic routing, spectrum allocation.
