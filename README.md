# Transformers-in-VQA: A Comparative Study of Multimodal and Single-Modality Fusion Approaches

## Abstract

Visual Question Answering (VQA) is a task that involves answering questions related to images or videos, and has experienced significant advancements in recent years. Despite the progress, there is a lack of comprehensive comparison between single-modality and multimodal transformers in VQA. VQA models must understand and integrate information from both textual and visual sources.

In this study, we compare two different approaches:
1. **Single Modality Fusion**: In this approach, language and vision features are independently extracted via RoBERTa (for text) and Beit (for images) and are fused at a later stage.
2. **Multimodal Fusion**: This approach uses BLIP, a state-of-the-art vision-language model that jointly encodes both text and image modalities.

We implement standardized preprocessing, training, and evaluation pipelines to ensure fairness and consistency in results. The findings from this study will provide insights into optimizing model design for enhanced accuracy, efficiency, and real-world applicability.

## Features
- Comparison between single-modality and multimodal transformers for VQA.
- Standardized pipelines for preprocessing, training, and evaluation.
- In-depth analysis of model performance and insights for optimization.


