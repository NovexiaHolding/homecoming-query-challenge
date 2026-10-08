# homecoming-query-challenge

Perheäly / Novexia Holding – ICT Student Recruitment Challenge v1.0

## 🚦 Challenge 1: Homecoming Query API v1.0

### Description
Implement a clean and modular code snippet (approx. 30–60 lines) that triggers upon connecting to home Wi-Fi and queries the user's homecoming state using a 5-level traffic light scale.

### Homecoming States (Status Enum):
* 🟢 **GREEN** (Fully charged / Open)
* 🟩 **LIME** (Charging / Normal routine)
* 🟡 **YELLOW** (15-min timeout needed)
* 🟠 **ORANGE** (Low tolerance / Needs peace)
* 🔴 **RED** (Emergency mode / Total rest)

### Requirements:
1. **Trigger:** Detect home Wi-Fi connection (or provide simulation/mocking for testing).
2. **Query:** Prompt the user to select their homecoming state.
3. **Clean Output:** Return the user selection in standard JSON format (e.g., Event, Status, Timestamp).

### Evaluation Criteria:
* **Clean Code:** Clear, structured, and readable implementation.
* **Testability:** Easy way to simulate Wi-Fi triggers without physical network switches.
* 
