# Naija Kitchen - Nodecademy

A responsive food website showing Nigerian dishes, built for Nodecademy week-02.

## Built With
. HTML5
 .CSS3 (Flexbox, Grid, transitions)

## Live Link
https://aminaoyiza12.github.io/nodecademy/

## Bug I Fixed
Fourth time my teacher asked for README.
Main bug: I had `transition: transform 0.2s case` in my gallery cards. `case` is not valid, should be `ease` - so animation was broken. Also my shadow `rgba(0,0,0,0.01)` was invisible, I fixed to `0.15`. I fixed it in commit "fix card ribbon".

## What I Learned
. How position: relative on hamburger parent and absolute on red dot makes notification dot
. Difference between transition (needs hover) and @keyframes (animates alone)
