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

- mininglevel(default: 1)

    - Hash value need to start with mininglevel times '0' as mining rule

- goal(default: 3)

    - Need to create this numbers of block for clearing game.


## Licensing

This code is licensed under MIT.

https://github.com/dotnsf/nonce/blob/master/LICENSE


## Copyright

2019-2020 [K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.
