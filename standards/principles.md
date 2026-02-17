# Visualisation Principles

These principles define the minimum standard for data visualisation produced by the Health Economics Unit.  
They are designed to promote clarity, consistency, transparency and accessibility across our analytical outputs.

---

## 1. Clarity over decoration

- Choose simple, interpretable chart types.
- Avoid unnecessary visual effects (3D charts, gradients, drop shadows).
- Reduce visual clutter (limit gridlines, minimise chart junk).
- Use titles that communicate the key message, not just the metric name.

The purpose of a visual is to support decision-making — not to decorate a slide.

---

## 2. Be accurate and transparent

- Avoid misleading scales or truncated axes unless clearly justified.
- Always include units (%, rate per 100,000, £, QALYs, etc.).
- Clearly state time periods and denominators.
- Label provisional, modelled or incomplete data appropriately.
- Where assumptions are used, ensure they are documented in accompanying text.

Visualisations must accurately reflect the underlying data and assumptions.

---

## 3. Show uncertainty where appropriate

Uncertainty is a core feature of health economic and analytical work.

Where relevant, include:

- Confidence intervals
- Interquartile ranges
- Prediction intervals
- Scenario ranges
- Probabilistic sensitivity analysis outputs
- Distributions (e.g. histograms, density plots)

Uncertainty should be explained clearly so that interpretation is not ambiguous.

---

## 4. Ensure accessibility

All outputs should be accessible to a wide audience.

- Use colour-blind safe palettes.
- Do not rely solely on red/green distinctions.
- Use sufficient font sizes for slide decks.
- Ensure adequate contrast between text and background.
- Prefer direct labelling to reduce reliance on legends.

Accessibility improves clarity for everyone, not just those with impairments.

---

## 5. Maintain consistency

Consistency improves professionalism and interpretability.

- Use the Health Economics Unit templates where possible.
- Apply consistent date formats, axis labelling and units within a report.
- Align chart styling across sections of the same presentation.
- Avoid mixing multiple stylistic approaches in a single output.

Consistency builds trust in analytical outputs.

---

## 6. Match the visual to the question

Choose the chart type based on the analytical question:

- Trends over time → line chart
- Distribution → histogram, density or boxplot
- Comparison across groups → bar chart or dot plot
- Variation across organisations → funnel plot
- Survival analysis → Kaplan–Meier curve
- Cost-effectiveness → CE plane and CEAC

The visual should make the answer to the question easier to see.

---

## 7. Design for the audience

Consider:

- Who is the audience? (technical vs executive)
- What decision are they being asked to make?
- How much context do they have?

Executive audiences may require simplified visuals with clear takeaways.  
Technical audiences may require fuller representation of assumptions and uncertainty.

---

## 8. Reproducibility and governance

Where possible:

- Visualisations should be reproducible from code.
- Data sources should be traceable.
- Outputs shared externally must meet governance and information governance requirements.

Transparency supports credibility and public trust.

---

These principles should guide all visual outputs produced by the Health Economics Unit.
Templates provided in this repository operationalise these standards for Python and R.
