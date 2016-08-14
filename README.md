# Android Basics Nanodegree project 1 

We had to build a single-screen app in this project, so I built an app I can show the [MU chess club](https://sites.google.com/site/umcchess/), housed at the [University of Missouri-Columbia](http://missouri.edu/).

Like a business card, this app directs users to the official club website and contact e-mail address. I may update it later with a button that submits an email request to join MUCHESS-L Listserv. 

###### Table of contents
1. [Preview images](#preview-images)
2. [Project notes](#project-notes)


# 
## Preview images

# 
#### Nexus 4 preview


![image](https://raw.githubusercontent.com/devted/ABNDp1/master/app/src/main/res/layout/project-notes/app_preview_muchess_Nexus4.png)


# 
#### Nexus 5X preview
![image](https://raw.githubusercontent.com/devted/ABNDp1/master/app/src/main/res/layout/project-notes/app_preview_muchess_Nexus5X.png)


# 
#### Nexus 10 tablet landscape preview
![image](https://raw.githubusercontent.com/devted/ABNDp1/master/app/src/main/res/layout/project-notes/app_preview_muchess_Nexus10.png)


# 
## Project notes

# 
I first downloaded a free Creative Commons CC0 chessboard background from [Pixabay.com](https://pixabay.com/static/uploads/photo/2015/03/18/10/32/chess-679093_960_720.jpg), then ran it through a couple of image transfirmations to make it black and gold. 

![image](https://raw.githubusercontent.com/devted/ABNDp1/master/app/src/main/res/layout/project-notes/app_design_before_and_after_chessboard.png)

# 
I then took the image from the MUChess homepage and made it transparent.

![image](https://raw.githubusercontent.com/devted/ABNDp1/master/app/src/main/res/layout/project-notes/app_design_before_and_after_muchess.png)

# 
#### also

# 
- Since I needed ImageViews and TextViews on the background, the project uses a **RelativeLayout** view group. 
- So the background expands on tablets, it uses "centerCrop" for scaleType, and "match_parent" for layout_width and layout_height.
- Build in Android Studio with Build --> Rebuild Project. 

