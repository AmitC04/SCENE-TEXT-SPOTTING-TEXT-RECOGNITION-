# SCENE-TEXT-SPOTTING-TEXT-RECOGNITION-
CREATED A ML MODEL : FOR A SMALL DATASET , CAN BE FURTHER EXPAND USING THE LARGE DATASET LIKE  TOTALTEXT, etc.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README</title>
</head>
<body>
    <h1>Scene Text Spotting and Text Recognition</h1>
    <p>
        Welcome to the <strong>Scene Text Spotting and Text Recognition</strong> repository! This project is designed for robust text detection and recognition in natural scenes, leveraging state-of-the-art machine learning techniques.
    </p>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#datasets">Datasets</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
    </ul>

    <h2 id="overview">Overview</h2>
    <p>
        This repository provides tools and models for detecting and recognizing text in natural scene images. 
        The pipeline integrates text detection and recognition for end-to-end text spotting.
    </p>

    <h2 id="features">Features</h2>
    <ul>
        <li>End-to-end scene text detection and recognition.</li>
        <li>Support for various datasets, including ICDAR and TotalText.</li>
        <li>Modular and extensible architecture for easy customization.</li>
        <li>Pre-trained models for quick inference.</li>
    </ul>

    <h2 id="installation">Installation</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/AmitC04/SCENE-TEXT-SPOTTING-TEXT-RECOGNITION.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd SCENE-TEXT-SPOTTING-TEXT-RECOGNITION</code></pre>
        <li>Install required dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
    </ol>

    <h2 id="usage">Usage</h2>
    <p>
        To perform text spotting on a given image, use the following command:
    </p>
    <pre><code>python main.py --image path/to/image.jpg</code></pre>
    <p>
        For more detailed options, refer to the <code>main.py</code> script.
    </p>

    <h2 id="datasets">Datasets</h2>
    <p>
        This project supports several popular datasets for training and evaluation:
    </p>
    <ul>
        <li><a href="https://rrc.cvc.uab.es/?ch=4">ICDAR 2015</a></li>
        <li><a href="https://github.com/cs-chan/Total-Text-Dataset">TotalText</a></li>
        <li>Custom datasets can also be integrated following the data format guidelines.</li>
    </ul>

    <h2 id="contributing">Contributing</h2>
    <p>
        Contributions are welcome! To contribute:
    </p>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a new branch for your feature or bug fix:</li>
        <pre><code>git checkout -b feature-name</code></pre>
        <li>Commit your changes and push to the branch:</li>
        <pre><code>git push origin feature-name</code></pre>
        <li>Submit a pull request.</li>
    </ol>

    <h2 id="license">License</h2>
    <p>
        This project is licensed under the <a href="LICENSE">MIT License</a>.
    </p>

    <footer>
        <p>
            Created by <a href="https://github.com/AmitC04">AmitC04</a>. For any queries or issues, please open an 
            <a href="https://github.com/AmitC04/SCENE-TEXT-SPOTTING-TEXT-RECOGNITION/issues">issue</a>.
        </p>
    </footer>
</body>
</html>

