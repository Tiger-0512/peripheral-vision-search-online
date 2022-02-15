# Online Experiments for Creating a Fair Display Regardless of the Retinal Eccentricity

## Dependencies
- Psychopy 2021.1.4

## Usage
### 1. Local
1. Start PsychoPy
2. Open `.psyexp` file in each experiment's directory <br>
  e.g. [`peripheral-visual-search-online/1a_imagenet/peripheral-search.psyexp`](https://github.com/Tiger-0512/peripheral-visual-search-online/blob/main/1a_imagenet/peripheral-search.psyexp)
3. Execute the experiment (Click "Run experiment" button in the menu bar)
### 2. Online
1. Start PsychoPy
2. Open `.psyexp` file in each experiment's directory
3. Push the experiment on Pavlovia (Click "Sync with web project" button in the menu bar) <br>
  If you don't have an account on Pavlovia, you have to create it.
4. Open https://pavlovia.org and log in.
5. Excute the experiment on your dashboard.

If you want to know the procedure in detail, please read [my article on qiita](https://qiita.com/Tiger-0512/items/32459e4450da3db49217) (written in Japanese) or contact me.

## Notice
- Please use PsychoPy Builder to modify the experiment. <br>
  Each of the `.js` and `.py` files is generated by runnning `.psyexp` file corresponding to it. <br>
  For that reason, the `.js` and `.py` files are very complicated and hard to read.
- You don't necessarily have to use Pavlovia as the host server. <br>
  For example, you can use your own server or use other system. <br>
  However, I think that Pavlovia provides one of the simple and easy way to deploy your experiment.
