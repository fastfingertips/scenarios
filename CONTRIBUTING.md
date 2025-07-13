# Contributing

We'd love to add your routine! Here's how to contribute.

### Contribution Steps

1.  **Choose a folder:** Pick the best category for your routine (e.g., `/personal`, `/work`).
2.  **Name your file:** Use lowercase and hyphens (e.g., `after-a-coffee-break.yaml`).
3.  **Use the template:** Copy the structure below for your file's content.

After creating your file, open a Pull Request.

### Scenario Template

```yaml
# scenario: "A short, clear title for the situation"
# description: "A brief explanation of when this scenario is triggered."
# tags: ["optional", "tags"]
# next_steps:
#   - step: "Name of the first action"
#     priority: "high" # high, medium, or low
#     estimated_duration_min: 5
#     required_energy: "low" # high, medium, or low
#     notes: "A helpful tip or an extra detail."
#   - step: "Name of the second action"
#     priority: "medium"
#     estimated_duration_min: 15
#     required_energy: "medium"
#     notes: "Keep notes concise and actionable."