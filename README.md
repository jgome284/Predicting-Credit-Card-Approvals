# Predicting Credit Card Approvals
<br />
<p align="center">
  <a href="https://github.com/jgome284/Predicting-Credit-Card-Approvals">
    <img src="images\credit-card.jpg" alt="Logo" width="465" height="262">
  </a>

  <h3 align="center">Foreword</h3>

  <p align="center">
    This project demonstrates a logistic regression classification model to automate credit card approvals.
    <br />
    <a href="https://github.com/jgome284/Predicting-Credit-Card-Approvals/issues">Report Bug</a>
    ·
    <a href="https://github.com/jgome284/Predicting-Credit-Card-Approvals/issues">Request Feature</a>
  </p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents
<div style='text-align:'>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#environment">Installation</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project
[Predicting Credit Card Approvals](https://github.com/jgome284/Predicting-Credit-Card-Approvals)

Banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In [this notebook](notebook.ipynb), an automatic credit card approval predictor is built using machine learning techniques.

<!--
You can include tables or images to summarize your results when and if appropriate.
-->

<!-- GETTING STARTED -->
## Getting Started

To recreate this project locally, you can clone this repository via HTTPS as follows.

```sh
git clone https://github.com/jgome284/Predicting-Credit-Card-Approvals.git 
```
### Environment
Virtual environments are a great way to keep your system-wide Python installation clean and organized. Each virtual environment is isolated from the others, so changes you make to the packages in one virtual environment will not affect the packages in another virtual environment. This can help to prevent conflicts between packages that are used by different projects.

**Create**

 You can create a virtual environment named my_env to manage this projects dependencies, for example. To do so, run the following command:
```sh
python3 -m venv my_env
```

**Activate**

To activate the virtual environment, run the following command:
```sh
source my_env/bin/activate
```

**Deactivate**

To deactivate the virtual environment, run the following command:
```sh
deactivate
```

### Dependencies
Python version 3.9.6 was used to run this analysis. To install additional dependencies, run the following command:
```sh
pip install -r requirements.txt
```
Best practice is to install these dependencies into an activated virtual environment. ```pip``` should be smart enough to handle dependencies between all packages required during installation.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.