# Chapter 1: Introduction

Notes on *Data Science from Scratch* by Joel Grus.

## The Ascendance of Data

Data is everywhere, and today it is produced in huge amounts within fractions of a second: social media, smart homes, cars, and more. From this data we extract patterns and insights, and it can lead us to questions that no one had thought to ask.

## What Is Data Science?

> We'll say that a data scientist is someone who extracts insights from messy data.

A data scientist turns noisy or raw data into insights. The book gives real examples where data scientists played a key role, such as the US elections and a retailer that tried to identify pregnant customers in order to target them with ads.

## Finding Key Connectors

In the friendships example, what stood out to me is that a plain list of names and IDs turned into useful questions:
- Who are each user's friends, and how many?
- Which user has the most friends, and which has the fewest?

We also got a better way to display the network: the bigger the node, the more connections it has. Looking only at the original dictionary, we might never have asked these questions. This is a small example of why data scientists matter.

## Other Examples

The remaining examples follow the same idea: simple data and simple tools (`Counter`, `defaultdict`) lead to useful answers.

| Example | Idea | Covered properly in |
|---|---|---|
| Data Scientists You May Know | Suggest users by mutual friends and shared interests | Ch. 23 |
| Salaries and Experience | Average salary by experience bucket | Ch. 14 |
| Paid Accounts | Predict who pays based on years of experience | Ch. 16 |
| Topics of Interest | Most popular interests by word count | Ch. 21 |

These solutions are rough first attempts; later chapters replace them with proper methods.

## Vocabulary

| Term | Meaning |
|---|---|
| Quantified selfers | People who track data about themselves with devices and apps (steps, sleep, heart rate) |
| Key connectors | The most connected users in a network, i.e. those with the most friends |
