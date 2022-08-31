## Galaxai

Galaxai a graph-like networking platform that aims to bring the AI/ML community in the MENA region closer, in Galaxai people are represented as nodes in a huge graph, the more similar these people are the closer they are in the Galaxai.  

You get to explore people in the graph space, engage in conversations, exchange experiences and knowledge, sell/ buy locally collected datasets, invite people to your events and get freelancing and collaboration opportunities with people in the community.

Researcher you are, AI engineer, data enthusiast or a student with ml background you make the community, you make Galaxai.


<img style="display: block;margin-left: auto;margin-right: auto;" width="600px" src="figures/graph1.png" >

## issues we want to address

The ML and AI community in the MENA region is scattered, and so are their efforts, we aim to bring the community together and encourage it to engage in serious discussions to solve real-world problems.

we aim to answer the following questions for our users : 
- who can I collaborate with ?
- on what should we work on ?
- who should I ask for help in case needed ? 

and provide the following services :
- data market : share publicy, sell or buy data-sets.
- events : share with and invite the community to your organized events.
- freelance and collaborate : create contracts and collaborate with other people in the community. 

## our philosophy 

- linked-in is not cool, graphs are cool.
- we want for our platform to be focused on people not posts.
- the social feed in other platforms is full of noise, irrelevant voices and distractions.
- in other networks users are always trapped by social bubbles, little do they explore and discover new people.
- in Galaxia we have no likes, no private/ public, no every-day selfies, no more irrelevancy, just pure networking.
- Galaxia is about a one wielded community.

## how it works ?

Each individual create a profile on our platform, includes a short summary, area of work, his experiences and certification, Galaxia measures similarity between members of community and bring most similar ones closer. 

## prototype 

**pilot ideas** :

- how we can represent and visualize people in the community as a 3d **graph** ?
- how to **measure similarity** between different profiles  ?

steps we followed : 

- we constructed a toy dataset, handful of users profiles.
- using pre-trained bert model we embed user's profiles.
- we measure the cosine similarity across the embeddings.
- we use 3js to visualize construct a 3d graph representation in the browser.

**to test it out** : 

### **measure similarity**

- clone repo :
```
git clone https://github.com/1hachem/ML-Graph
```
- install dependencies :
```
conda env create -f environment.yml
```
- follow `similarity_measure.ipynb` notebook to get an idea on how we measure similarity across users.
 
### **graph view**
- run a localhost and open `index.html` in you browser.

## show me the moneeeeeyyy !
<img src="figures/so-wheres-my-money.jpg" style="display: block;margin-left: auto;margin-right: auto;" width="200px">

The main functionality of Galaxia is free for the community, 
however we intend on making it profitable with premium features.

|features|fermium|premium|
|--------|-------|-------|
|price| free |9$/month|
|graph-like networking| ✓ | ✓ |
|unlimited messages| ✓ | ✓ |
|unlimited depth of view| ✓ | ✓ |
|event posting|x|✓|
|filters|up to 3| unlimited number|
|freelance fee| 20% | 10% |
|data market sells fee|17%| 15%|
|data host limit|<2GB|<20GB|


