# AI-agent-driven-Verilog-and-UVM-Generator

This project implements an automated AI-assisted RTL design and verification workflow using n8n, Google Gemini, Google Docs, and Icarus Verilog.

The pipeline allows a user to describe a hardware design in chat, after which an AI agent:
- Generates synthesizable Verilog-2001 RTL
- Writes the code directly to Google Docs
- Automatically compiles the RTL using Icarus Verilog
- Detects and fixes compilation errors using an AI error-solver agent
- Updates the corrected RTL in the document
- Generates a complete UVM verification environment for the DUT

The workflow demonstrates how LLM agents can be integrated into hardware design flows, enabling automated RTL generation, compilation, debugging, and verification scaffolding.

Tech Stack:
- n8n workflow automation
- Google Gemini Chat Model
- Google Docs API
- Icarus Verilog
- SystemVerilog / UVM
