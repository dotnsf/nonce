# nonce

## Overview

Nonce simulator


## How to play

- Click **nonce** button until **hash** button turns to be green, which means hash value of body, nonce(, and previous hash ) can be passed from mining rule.

- Then you can click **hash** button to create block.

- Repeat this behavior for some certain number.


## Table column header

- # : Number of block

- body : Randomly generated JSON object

- nonce: current nonce number

- hash : current hash value of body, nonce, and previous hash after block \#2.

- block : generated block


## URL Parameters

- mining(1)

    - Hash value need to start with mining times '0' as mining rule

- goal(3)

    - Need to create this numbers of block for clearing game.


## Copyright

2019 [K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.
