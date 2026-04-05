# AI V&V Notebooks

A collection of Jupyter notebooks demonstrating AI/ML verification and validation (V&V) techniques, focusing on adversarial robustness and model reliability.

## Notebooks

| Notebook | Description |
|----------|-------------|
| `adversarial_traffic_light.ipynb` | Demonstrates adversarial attacks on image classification. Uses Foolbox to craft imperceptible perturbations that fool a pretrained ResNet-18 into misclassifying a traffic light as a tree. Highlights risks for safety-critical systems like autonomous vehicles. |
| `ML_robustness_for_demand_prediction.ipynb` | Compares ML model robustness for demand prediction. Trains neural networks and uses PyCaret for AutoML, then applies certified robustness analysis via auto_LiRPA to bound prediction changes under input perturbations. Includes a Gradio demo and W&B experiment tracking. |

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```
