<p align="center">
  <strong>Custom Company of Heroes Board Game assets</strong> provide alternative, printable assets than what is provided in the first edition of the Company of Heroes Board Game.
  <br>
  <img src="https://user-images.githubusercontent.com/3843505/126884463-a77fa041-d8dc-43cb-8a25-3a0849c1df59.png" alt="company-of-heroes">
</p>

## Digital Images Used In The Printed Game

I don't own any of the games branding or images, but there are ways to get them.  I snagged mine from the PDF rulebook.

If you want to generate your own files and use your own images, you can do so like this:

```
git clone https://github.com/jacobsalmela/company-of-heroes-board-game-assets.git
cd company-of-heroes-board-game-assets
mkdir -pv images/icons/{damage-types,unit-types}
# add images to the above folders
xelatex assets.tex
```

### Customizing Your Assets

You can customize your game by changing a few lines of code or importing your own images.  Some coding knowledge is required here.

### Feedback On The Assets In This Repo

To start, I only made a Defense Matrix, since people I played with had a hard time reading it.

<p><align="center">
<img src="https://user-images.githubusercontent.com/3843505/126902733-77bd5d77-dd05-4a25-a080-8020b2234c97.png" alt="custom-defense-matrix">
</p>

Submit feedback by [filling out the template](https://github.com/jacobsalmela/company-of-heroes-board-game-assets/issues/new?template=feedback.md).  Feel free to add additional comments as necessary.  

## Background

[The Company of Heroes Board Game](https://boardgamegeek.com/boardgame/281515/company-heroes) was released as a Kickstarter project.  As players got their hands on the game, they had a lot of feedback, enough so that the developers began working on a `v1.5` of the game to implement much of this feedback.

The game is incredibly fun, but I didn't want to wait, so I began building my own assets in LaTeX and printing them.

## Printing Real Cards And Other Assets

The rulebook is included on the [Releases page](https://github.com/jacobsalmela/ascii-planets/releases).

# Contributing

Contributions and pull requests are welcome!

# License

The images are not mine, nor are they licensed to me.  The code, however I wrote, so that is licensed under the Creative Commons license.
