<div id="top"></div>

# Number plate detection.


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      a href="#Results">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We trained mobilenetv2  architecture for number plate detection using 35k images you can find notebook to demo here 
Here's why:
* we selected mobilnetv2 because it needed less processing power and can easily run on iot devices 
* Takes less time to train the model 
* Higher fps even on low end devices :smile:


<p align="right">(<a href="#top">back to top</a>)</p>


### Results

![Train and Test loss](https://github.com/whoislimshady/mobilenet_v2_model_for_ocr/blob/master/inputs/download%20(1).png?raw=true)


<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

Frameworks/libraries used in  project. 

* [Tensorflow](https://www.tensorflow.org/resources/learn-ml)
* [Keras](https://keras.io/)
* [Jupyter notebook](https://jupyter.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
You can try running notebok in order to quickly test and train the model 
In order to set up  project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Install all the dependency in order to properly run the app.
* Requirements
  ```sh
  pip install -r requirements.txt
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/whoislimshady/mobilenet_v2_model_for_ocr
   ```
2. Install Requirements
  ```sh
  pip install -r requirements.txt
  ```


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

The trained model can later be used to solve security related issues
<p align="right">(<a href="#top">back to top</a>)</p>





<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



