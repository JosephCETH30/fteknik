---
description: Teknik Elektro
public: true
layout: ../../layouts/BlogPost.astro
title: Tensor Flow
createdAt: 1663138582918
updatedAt: 1663138612308
tags:
  - Teknik Elektro
heroImage: https://media.licdn.com/dms/image/D4E12AQE1Jzd6tFUu-w/article-cover_image-shrink_600_2000/0/1692018415350?e=2147483647&v=beta&t=BHr0iNRZfet1vLhJGaLM5y-CRLNQjpJTXLep1ZUCH24
slug: teknikelektro
---

The use of AI-generated simulations in conjunction allows the project team to make informed construction and design choices by using data-driven insights on possible outcomes and alternatives. 

Electrical engineering is a branch of engineering that deals with the study, design, and application of equipment, devices, and systems which use electricity, electronics, and electromagnetism. It encompasses a wide range of subfields, including power engineering, control systems, electronics, microelectronics, signal processing, telecommunications, and instrumentation.

Power Engineering: Deals with the generation, transmission, distribution, and utilization of electric power. This includes working with transformers, generators, motors, and power electronics.

Control Systems: Focuses on designing and implementing control systems for dynamic systems in various applications like robotics, automotive systems, and industrial automation.

Electronics: Involves designing and developing electronic circuits, devices, and systems. This includes microprocessors, semiconductors, and integrated circuits.

Telecommunications: Covers the transmission of information across channels like fiber optics, satellite communication, and wireless networks.

Signal Processing: Involves the analysis, interpretation, and manipulation of signals. This is critical in areas like audio processing, image processing, and communications.

Instrumentation: Focuses on the design and configuration of devices that measure physical quantities like temperature, pressure, and flow.


<br>

### Tensor Flow : TensorFlow is a tool for machine learning capable of building deep neural networks with high-level Python code.
<br>

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/i8NETqtGHms" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<br>

### 1. Famous Open Source Machine Learning Software for Electrical Engineering
<br>
-> TensorFlow is an Open-source AI Framework taht is a favorite among electrical engineers for developing deep learning models. Whether you're an expert or a beginner, TensorFlow is an end-to-end platform that makes it easy for you to build and deploy ML models.<br><br>

### 2. Easy model building
<br>
-> TensorFlow offers multiple levels of abstraction so you can choose the right one for your needs. Build and train models by using the high-level Keras API, which makes getting started with TensorFlow and machine learning easy.
 <br><br>

### 3. Robust ML production anywhere
<br>
-> TensorFlow has always provided a direct path to production. Whether it's on servers, edge devices, or the web, TensorFlow lets you train and deploy your model easily, no matter what language or platform you use. Use TFX if you need a full production ML pipeline. For running inference on mobile and edge devices, use TensorFlow Lite. Train and deploy models in JavaScript environments using TensorFlow.js.
 <br><br>


### 4. Powerful experimentation for research
<br>
-> Build and train state-of-the-art models without sacrificing speed or performance. TensorFlow gives you the flexibility and control with features like the Keras Functional API and Model Subclassing API for creation of complex topologies. For easy prototyping and fast debugging, use eager execution. TensorFlow also supports an ecosystem of powerful add-on libraries and models to experiment with, including Ragged Tensors, TensorFlow Probability, Tensor2Tensor and BERT. 
<br><br>

### Get started with TensorFlow
TensorFlow makes it easy to create ML models that can run in any environment. Learn how to use the intuitive APIs through interactive code samples.
<pre style="background: #222222; padding: 25px 10px;">
import tensorflow as tf
mnist = tf.keras.datasets.mnist

(x_train, y_train),(x_test, y_test) = mnist.load_data()
x_train, x_test = x_train / 255.0, x_test / 255.0

model = tf.keras.models.Sequential([
  tf.keras.layers.Flatten(input_shape=(28, 28)),
  tf.keras.layers.Dense(128, activation='relu'),
  tf.keras.layers.Dropout(0.2),
  tf.keras.layers.Dense(10, activation='softmax')
])

model.compile(optimizer='adam',
  loss='sparse_categorical_crossentropy',
  metrics=['accuracy'])

model.fit(x_train, y_train, epochs=5)
model.evaluate(x_test, y_test)
</pre>


<div style="text-align: center; margin-top: 20px;">
  <a href="https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/quickstart/beginner.ipynb" target="_blank" style="display: inline-block; padding: 12px 23px; font-size: 20px; font-weight: bold; color: #ffffff; background-color: #3a6cf4; text-decoration: none; border-radius: 5px;">Run Quickstart Google Collab</a>
  <a href="https://www.tensorflow.org/" target="_blank" style="display: inline-block; padding: 12px 23px; font-size: 20px; font-weight: bold; color: #ffffff; background-color: #3a6cf4; text-decoration: none; border-radius: 5px;">Visit Tensor Flow</a>
</div>

<br>
AI tidak sepenuhnya bisa mengerjakan apa yang kalian mau, tapi bisa membantu mengakselerasi pengerjaan Tugasmu dan ingat selalu bahwa Penggunaan Seketika bisa berubah dan Tools akan terus diupdate mengikuti Perkembangan Zaman, Terimakasih.
