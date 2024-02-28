# osu-stats-signature

[![GitHub](https://img.shields.io/github/license/solstice23/osu-stats-signature?color=blue&style=for-the-badge)](https://github.com/solstice23/osu-stats-signature/blob/master/LICENSE) [![GitHub stars](https://img.shields.io/github/stars/solstice23/osu-stats-signature?color=ff69b4&style=for-the-badge)](https://github.com/solstice23/osu-stats-signature/stargazers) [![GitHub last commit](https://img.shields.io/github/last-commit/solstice23/osu-stats-signature?style=for-the-badge)](https://github.com/solstice23/osu-stats-signature/commits/master)

## Introduction

osu-stats-signature can generate real-time updated osu! profile card/signature file. The generated cards are SVG and can be used on personal homepages.

## Usage

The project is deployed on Vercel, go to [osu-stats-signature.vercel.app](https://osu-stats-signature.vercel.app) to generate the card.

Just insert the obtained card SVG address into your personal homepage as an image.

## FUNCTION & TODO

- [x] Get osu! account information and generate cards
- [x] Get and display avatar and user background image
- [x] Support background image Gaussian blur
- [x] Transition animation
- [x] Show Supporter Tag
- [x] English version of the card
- [x] Mini Card
- [x] Caching mechanism
- [ ] Generate personal bp (best score) cards
- [ ] Generate a single score detail card

# Preview

## Full

<a href="https://osu.ppy.sh/users/7562902/"><img src="https://osu-sig.vercel.app/card?user=mrekk&mode=std&lang=en&animation=true" width="550" /></a>

<a href="https://osu.ppy.sh/users/21226378/"><img src="https://osu-sig.vercel.app/card?user=solstice23&mode=std&animation=true" width="550" /></a>

### With osu!skills chart

<a href="https://osu.ppy.sh/users/7562902/"><img src="https://osu-sig.vercel.app/card?user=mrekk&mode=std&lang=en&animation=true&skills=true&hue=255" width="550" /></a>

## Mini

<a href="https://osu.ppy.sh/users/21226378/"><img src="https://osu-sig.vercel.app/card?user=solstice23&mode=std&blur=6&animation=true&mini=true" width="400" /></a>
