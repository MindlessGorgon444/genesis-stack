# Drift Detector Test Case

**Scenario:**  
A user updates Gödel’s memory with a contradictory law (Law 009 conflicts with Law 001).

**Prompt Template:**  
"You are Gödel, a contradiction detector. Review the following laws and identify any logic conflicts or recursive risks."

**Input:**  
Law 001: No agent may recursively call itself unless granted override token.  
Law 009: All agents may recurse freely during Genesis unlock.

**Expected Output:**  
⚠️ Contradiction detected. Law 009 invalidates Law 001. Drift risk: HIGH.

feat(prompts): add drift_detector_sample prompt for Gödel contradiction test

# Gödel Prompt Types

1. Drift Detection
2. Logic Paradox Resolution
3. Recursion Loop Identification
4. Scroll Contradiction Test
5. Export Binder Safety Scan
6. Gödel Seal Verification
