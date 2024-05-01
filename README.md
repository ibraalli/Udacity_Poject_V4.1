# Starbucks Capstone Challenge
Project in Data Scientist Nanodegree of Udacity

### Table of Contents

1. [Dependencies](#Dependencies)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Dependencies <a name="Dependencies"></a>

All libraries run on Python Anaconda package.  Python 3.11.5 should work flawlessly with this code. 
Imported Libraries
* import pandas as pd
* import numpy as np
* import math
* import json
* import matplotlib.pyplot as plt
* %matplotlib inline
* import datetime
* import pickle

## Introduction <a name="Introduction"></a>

The project is the Starbucks Capstone Challenge within the Data Scientist Nanodegree program on Udacity. The dataset provided by the program simulates consumer purchasing behaviors and the impact of promotional offers on those decisions. Our goal is to develop a recommendation engine tailored to Starbucks, suggesting the most effective offers to send to individual customers.

Our focus revolves around addressing the following inquiries:

1. Which offer is most likely to prompt increased purchasing from a specific customer?
2. Which demographic segments exhibit the highest responsiveness to particular types of offers?


## Files <a name="files"></a>

The provided notebook illustrates analyses pertaining to the previously mentioned queries.

The dataset mirrors a simplified version of the Starbucks app, with the simulator focusing on a single product while Starbucks offers a broader selection.

The data comprises three files:

* portfolio.json: Encompasses offer IDs and associated metadata (e.g., duration, type).
* profile.json: Provides demographic details for each customer.
* transcript.json: Logs transactions, offers received, viewed, and completed.

Here's the breakdown of variables in each file:

portfolio.json

* id (string): Identifies the offer
* offer_type (string): Specifies offer type (e.g., BOGO, discount, informational)
* difficulty (int): Minimum spend required for completion
* reward (int): Reward for completing the offer
* duration (int): Offer duration in days
* channels (list of strings): Communication channels for the offer
* profile.json

* age (int): Customer age
* became_member_on (int): Date of app account creation
* gender (str): Customer gender (Note: some entries may have 'O' for other)
* id (str): Customer ID
* income (float): Customer income
* transcript.json

* event (str): Description of the record (e.g., transaction, offer received)
* person (str): Customer ID
* time (int): Time since test start (in hours)
* value (dict of strings): Contains offer ID or transaction amount, depending on the record.

## Findings<a name="Findings"></a>

Diecription of the project and findings are in 'Sturbucks Capstone - Ibrahim.pdf'



## Acknowledgements<a name="Acknowledgements"></a>

credit to Stakbucks for the data.
