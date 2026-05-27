# Codex Instructions for OrthoScan AI

Use the Superpower plugin while working.

Use CodeGraph before editing:
- Start by asking CodeGraph for project structure and important symbols.
- Use CodeGraph to inspect FastAPI routes, React components, IMU pipeline functions, and model-loading logic.
- Use normal file reading only after CodeGraph points to the relevant files.

Important areas:
- api/main.py
- rehab_platform/core/imu_pipeline.py
- frontend/src/App.jsx
- rehab_platform/SETUP.md

Do not commit:
- .codegraph/
- node_modules/
- large CSV/ZIP/model artifacts unless explicitly required.
