# AeroFormer - Real-Time Weather Intelligence for Pilots
#### We pair a route-semantic weather matrix with dual LLM engines-one translator, one executive co-pilot—to collapse the time between encoded bulletins and actionable flight decisions.


Problem: Raw aviation data (METAR/TAF) is highly encoded and fragmented, causing cognitive load and delays in critical safety decisions.

Solution: Built a dual-engine Qwen system fine-tuned via QLoRA and DPO, utilizing RAG and an RDF Knowledge Graph for semantic reasoning.

Result: Delivered hallucination-free narratives validated by NVIDIA NeMo guardrails, significantly accelerating "Go/No-Go" flight analysis.

Tech: LLMs (Qwen, Fine-tuning via QLoRA & DPO), Architecture (RAG, RDF Knowledge Graph), Safety (NVIDIA NeMo Guardrails, Hallucination Detection).


#### Operational Flow

<img width="1561" height="331" alt="Screenshot 2026-02-06 at 6 10 29 PM" src="https://github.com/user-attachments/assets/03db6d1b-c29e-46f8-9623-513710f99b87" />


#### Finetune with RALA-DPO
<img width="1370" height="557" alt="Screenshot 2026-02-06 at 9 08 52 PM" src="https://github.com/user-attachments/assets/d336f079-153b-4d09-8fda-62993c97af1d" />
