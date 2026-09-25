# Source / Workflow Scope

This project did not include an executable software package or original metrology-control code.

The main technical artifact is a **measurement-to-modeling workflow**:

```text
X-ray measurement
       ↓
Independent structural parameter
       ↓
Fixed constraint
       ↓
SE inverse model
       ↓
Reduced floating-variable space
       ↓
Density / roughness / optical-property interpretation
```

## Why There Is No Instrument Code

The submitted materials document:

- measurement principles
- model-fitting logic
- feed-forward constraint strategy
- literature comparison

They do not contain:

- instrument automation scripts
- original SE raw spectra
- original XRR raw reflectivity curves
- a custom fitting software implementation

Therefore this repository does not invent source code that was not part of the project.
