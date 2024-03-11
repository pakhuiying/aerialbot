A repository forked from [doersino/aerialbot](https://github.com/doersino/aerialbot) to obtain high-resolution google tiles.


## Usage

### Setup
Run the following commands to get it installed on your system:

```bash
$ git clone https://github.com/pakhuiying/aerialbot
$ python3 -m venv aerialbot
$ cd aerialbot
$ source bin/activate
$ pip3 install -r requirements.txt
```

### Running

Then run `getTiles.ipynb`, first you must already know the corner coordinates of the scene you wish to retrieve. Use google maps as a guide.


![What is this? It's a progress indicator. What does it do? It indicates progress.](demo.gif)
Source: [doersino/aerialbot](https://github.com/doersino/aerialbot)

### Examples

![2024-01-22](/aerialbot-2024-01-22T12.25.29-downward-1.319335,103.737142-2000x2000m-z20.jpg) 
Image retrieved from 22nd Jan 2024 at southwest and northeast corner coordinates: `(1.319010, 103.736650)` and `(1.319806, 103.737532)`, respectively.

![2024-02-11](/aerialbot-2024-02-11T17.00.57-downward-1.319335,103.737142-2000x2000m-z20.jpg) 
Image retrieved from 11st Feb 2024 at southwest and northeast corner coordinates: `(1.319000, 103.736650)` and `(1.319806, 103.737532)`, respectively.