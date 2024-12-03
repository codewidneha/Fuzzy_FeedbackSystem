

# Clinical Decision Support System (CDSS) Using Fuzzy Logic

This project implements a **Clinical Decision Support System** (CDSS) using fuzzy logic. The system evaluates clinical inputs, such as temperature, heart rate, and blood pressure, to suggest diagnostic decisions ranging from "Stable" to "Critical."

---

## Features

- **Inputs**:
  - **Temperature (°F)**: Low, Normal, High.
  - **Heart Rate (bpm)**: Bradycardia, Normal, Tachycardia.
  - **Blood Pressure (mmHg)**: Low, Normal, High.

- **Output**:
  - Diagnosis levels: **Stable**, **Alert**, and **Critical**.

- **Fuzzy Logic**:
  - Uses fuzzy rules to interpret inputs and compute the diagnosis.

- **Visualization**:
  - Graphical representation of membership functions.
  - Visualization of the diagnosis process.

---

## Requirements

Make sure the following Python libraries are installed:

- `numpy`
- `scikit-fuzzy`
- `matplotlib`

You can install them using:

```bash
pip install numpy scikit-fuzzy matplotlib
```

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/cdss-fuzzy-logic.git
   cd cdss-fuzzy-logic
   ```

2. **Run the script**:
   ```bash
   python cdss_fuzzy_logic.py
   ```

3. **Input clinical parameters**:
   - Enter the temperature, heart rate, and blood pressure as prompted.

4. **View the output**:
   - The script computes and displays the diagnosis level and suggested action.

---

## Visualization

The project includes visualizations for:

1. **Membership Functions**:
   - Displays the fuzzy sets for each input and output variable.

2. **Diagnosis Process**:
   - Shows the computed diagnosis with a visual representation of fuzzy rules.

---

## Example Output

**Input:**
- Temperature: 100°F
- Heart Rate: 110 bpm
- Blood Pressure: 150 mmHg

**Output:**
```
Diagnosis Level: 87.45
Decision: Critical condition. Immediate medical attention required.
```

**Graphical Visualization:**
1. Membership function plots.
2. Diagnosis level visualization.

---

## File Structure

```
cdss-fuzzy-logic/
├── cdss_fuzzy_logic.py       # Main Python script for the CDSS
├── README.md                 # Project documentation
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

---

## Author

[Your Name](https://github.com/your-username)  
3rd-year student passionate about data structures, algorithms, and Java.
