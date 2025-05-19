# Shelf Auditing Synthetic Data

We're excited to open source our synthetic dataset project developed in collaboration with Tiendas Industriales Asociadas Sociedad Anónima (TIA S.A.), a leading grocery retailer in Ecuador. This dataset was created as part of a computer vision pipeline for automatic shelf auditing using synthetic data generated in a virtual 3D environment.

Our goal is to improve product placement accuracy and streamline audit processes using object detection and classification models trained on fully synthetic data.

## 📸 Sample Visualizations

Below are examples of SKU placements generated in the virtual store environment:

<p align="center">
  <img src="sample/colocacion_sku.png" width="400"/>
  <br><em>Vertical SKU placement</em>
</p>

<p align="center">
  <img src="sample/colocacion_sku_hz.png" width="400"/>
  <br><em>Horizontal SKU placement</em>
</p>

## 📁 Anexos

The `anexos/` folder includes a full list of all SKUs used in this project, along with their 3D representations and metadata.

## 📦 Datasets and Challenges

This repository introduces two main datasets:

### 🔹 RealSynthDet-15K

A detection dataset consisting of 15,000 synthetically rendered images containing multiple SKUs placed across a variety of shelving scenarios. This dataset is used for training object detection models.

### 🔹 ProdSynth-20

A classification dataset with isolated SKU renders across various angles and lighting conditions, covering 20 different product classes. This dataset supports fine-grained classification tasks.

#### ⚠️ Challenges

- Maintaining SKU diversity and realism in renderings.
- Balancing synthetic variability vs real-world constraints.
- Integration of Blender and Python pipelines for scalable dataset generation.

## 🙏 Acknowledgment

This work has been supported by the Tiendas Industriales Asociadas Sociedad Anónima (TIA S.A.). The authors would like to acknowledge TIA S.A., a leading grocery retailer in Ecuador, for providing access to an incredible environment for research and testing.
