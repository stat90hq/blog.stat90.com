---
title: "Quantifying On-Ball Threat in Football"
date: 2025-01-31
draft: false
description: "A deep dive into Expected Pass Threat (xPT) and Expected Carry Threat (xCT) to quantify how players create danger when on the ball"
tags: ["analytics", "metrics", "premier league", "2024-25"]
---

We start with the fundamental question: "What do players do when they have the ball?" Traditional statistics like assists and key passes tell part of the story, but they often miss the nuanced ways players influence the game. A player making consistent passes into dangerous areas or carrying the ball past defensive lines might not register traditional creative statistics, yet their actions consistently create threatening situations.

This led us to develop two new metrics - Expected Pass Threat (xPT) and Expected Carry Threat (xCT) - that aim to capture the full spectrum of a player's on-ball actions. Instead of just measuring end products like assists, these metrics evaluate every meaningful offensive action a player makes with the ball.

Consider this scenario: Player A makes five passes into the final third, while Player B makes two passes into the penalty area. Which player created more threat? To answer this objectively, we needed a baseline metric. We chose Expected Assisted Goals (xAG) as our foundation, using it to weight different actions based on how frequently they translate to actual creative output.

## The Two Dimensions of Threat

Let's dive straight into our main analysis. The visualization below plots every Premier League player's Expected Pass Threat (xPT) against their Expected Carry Threat (xCT), both measured per 90 minutes:

![xPt vs xCT (min 1100 minutes, all Premier League players until Jan 30, 2025)](top80_nopos_threat_scatter_dark.png)

The plot divides players into four distinct profiles:

1. **Complete Attackers** (Top Right): Players who excel at both passing and carrying threat
2. **Dribblers** (Top Left): Specialists in ball carrying who create danger through beating their man and carrying the ball into dangerous areas.
3. **Playmakers** (Bottom Right): Traditional creators who primarily threaten through their passing
4. **Conservative Players** (Bottom Left): Players who typically operate in less threatening areas or have more defensive responsibilities

### Position Clusters: Breaking Down the Playing Styles

The scatter plot reveals fascinating patterns in how different positions and roles cluster together, often challenging traditional positional classifications.

![xPt vs xCT (min 1100 minutes, all Premier League players until Jan 30, 2025)](top80_pos_threat_scatter_dark.png)

#### Creative Midfield Hubs
In the upper-middle region between Complete Attackers and Playmakers, we find an elite cluster of traditional "number 10s" and creative attacking midfielders. Cole Palmer, Martin Ødegaard, Bruno Fernandes, and James Maddison form a distinct group, all demonstrating balanced threat creation through both passing and carrying.

Two particularly interesting findings emerge here:
1. Mikkel Damsgaard and Dwight McNeil are positioned right among these elite creators, suggesting they might be undervalued for their creative contributions
2. Phil Foden appears slightly left of this cluster, indicating a potential dip in his creative output compared to his previous season's form where he would typically profile as a Complete Attacker

#### Deep-Lying Playmakers and Creative Fullbacks
Lower in the Playmaker quadrant, we find an intriguing mix of positions. Deep-lying midfielders like Enzo Fernandez and Youri Tielemans cluster together, but what's particularly noteworthy is how they're joined by attacking fullbacks such as Pedro Porro, Andy Robertson, and Pervis Estupiñán. This suggests modern fullbacks are taking on significant creative responsibilities, matching the threat creation of traditional midfield playmakers.

#### The Dribbling Specialists
The Dribblers quadrant showcases players who excel at progressing the ball through carries. Noni Madueke stands out significantly here, posting the highest carry threat numbers in the league. Just below him, we find an interesting cluster including Mohammed Kudus, Kaoru Mitoma, and Abdallah Sika Diallo, the latter's positioning reflecting his excellent recent form.

A notable outlier in this quadrant is Alejandro Garnacho, who shows strong carry threat but unusually low passing threat for his position, suggesting a more direct, dribbling-focused style.

#### Complete Attackers: The Elite Creators
The Complete Attackers quadrant is headlined by two standout performers: Mohamed Salah and Bukayo Saka, who are significantly ahead of their peers in both metrics. Behind them, we find a group of creative wingers including Dejan Kulusevski, Son Heung-min, Anthony Gordon, and Matheus Cunha, all demonstrating the modern winger's requirement to both create and progress the ball.

#### The Alexander-Arnold Effect
Perhaps the most striking individual case is Trent Alexander-Arnold, who posts unrivaled passing threat numbers that set him apart from every other player in the dataset. His positioning on the plot reflects his unique role as Liverpool's primary creative hub from a nominal right-back position.

### Team Case Study: [Team Name]

[INSERT: Analysis of one team's players and their distribution]

### Comparing Elite Creators

For players clustered in similar areas, we can break down their profiles further:

[INSERT: Radar chart comparing similar players]

## Top Performers

Let's look at the players leading in each metric:

### Top xPT Performers
[INSERT: Bar chart and analysis]

### Top xCT Performers
[INSERT: Bar chart and analysis]

## Technical Methodology

Now let's dive deeper into how these metrics are calculated.

Expected Pass Threat (xPT) combines several passing metrics, each weighted based on their correlation with xAG:
[INSERT: Full xPT calculation breakdown]

Expected Carry Threat (xCT) similarly weights carrying actions:
- Carries into Penalty Area: 0.180x xAG
- Successful Take-ons: 0.136x xAG
- Carries into Final Third: 0.086x xAG
- Take-on Attempts: 0.059x xAG
- Progressive Carries: 0.058x xAG

### Limitations

It's important to note that our weighting system looks at correlation rather than causation. While we can't track sequential actions within possessions, we believe this approach provides the best approximation given available data. We specifically chose positive attacking metrics that logically connect to threat creation, providing a robust framework for evaluation.

## What's Next?

While this analysis focuses primarily on creative roles, we're working on similar frameworks for other positions. Our next deep dive will look at the modern "6" role, analyzing how defensive midfielders influence the game through their on-ball actions.

[INSERT: Any closing thoughts or specific findings you'd like to highlight]