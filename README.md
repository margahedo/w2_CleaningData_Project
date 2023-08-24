# Data Cleaning Project: Shark Attack Analysis

This project focuses on the cleaning and analysis of a shark attack dataset. The goal is to explore, clean, and visualize the data to gain insights into shark attacks in different geographical regions. Additionally, a comprehensive examination of shark species has been conducted.

## Dataset Description

The dataset used for this project is located in the [attacks.csv] file and contains information about recorded shark attacks. The attributes included in the dataset are as follows:

- Case Number: Unique identifier for each shark attack case.
- Date: Date of the attack.
- Year: Year in which the attack occurred.
- Type: Type of the shark attack (e.g., provoked, unprovoked, etc.).
- Country: Country where the attack took place.
- Area: Specific geographic area where the attack occurred.
- Location: Detailed location information about the attack.
- Activity: Activity that the victim was engaged in at the time of the attack.
- Name: Name of the victim (if available).
- Sex: Gender of the victim.
- Age: Age of the victim.
- Injury: Description of the injuries caused by the attack.
- Fatal (Y/N): Indicates whether the attack resulted in the death of the victim (Y/N).
- Time: Time of the attack (if available).
- Species: Shark species involved in the attack.
- Investigator or Source: Source of the information about the attack.
- pdf, href formula, href: Columns related to additional file and hyperlink information.
- Case Number.1, Case Number.2, original order, Unnamed: 22, Unnamed: 23: Miscellaneous columns (not described in the dataset documentation).

In addition, a comprehensive examination of shark species has been performed, including information such as species name, habitat, and behavior.

## Dependencies and Environment Setup

1. Make sure you have Python installed along with the following libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn

2. Clone this repository to your local machine:

```
git clone https://github.com/your_username/your_project.git
```

3. Navigate to the project directory:

```
cd your_project
```

## Usage Instructions

1. Execute the [script_name.py] file to load and clean the data:

```
python script_name.py
```

2. Once the data is cleaned, use the [notebook_name.ipynb] notebooks to perform data analysis and visualization:

```
jupyter notebook notebook_name.ipynb
```

## Results and Conclusions

After analyzing the data on shark attacks, the following conclusions can be drawn:

1. The most frequently documented shark species in the recorded attacks is the **Carcharodon carcharias** (Great White Shark), with a total of 635 attacks. This species is known for its aggressiveness and large size, averaging 4 to 6 meters in length and weighing up to 2 tons.

2. Another species responsible for a significant number of attacks is the **Carcharias taurus** (Bull Shark) with 370 recorded attacks. Bull Sharks can grow over 3 meters in length and are known to be both curious and aggressive.

3. The **Galeocerdo cuviers** (Tiger Shark) also stands out with 255 recorded attacks. These sharks are known for their aggressive behavior and their ability to adapt to different marine habitats.

4. Several smaller shark species, such as the **Carcharhinus limbatus** (Blacktip Reef Shark) and the **Sphyrna mokarran** (Great Hammerhead Shark), are also present in the recorded attacks.

It is important to note that these data represent recorded information on shark attacks and should not be generalized to all interactions between sharks and humans. Water safety is crucial, and it is recommended to follow appropriate guidelines and precautionary measures when swimming or diving in areas where sharks may be present.

![Conteo de Ataques por Especie de Tiburón](count_by_species.png)


## Contributions

Contributions to this project are welcome. If you would like to suggest improvements, make changes, or add new features, you can submit a pull request for review.
## Links & Resources

- <https://www.kaggle.com/teajay/global-shark-attacks>
- <https://numpy.org/doc/1.18/>
- <https://pandas.pydata.org/>
- https://docs.python.org/3/library/functions.html
- https://plotly.com/python/
- https://matplotlib.org/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/docs/
- https://towardsdatascience.com/beware-of-storytelling-with-data-1710fea554b0?gi=537e0c10d89e
