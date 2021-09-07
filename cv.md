# Alaksandr Afanasienka

## Contacts:

* **Telegram:** <https://t.me/sanya2020327>

* **E-mail:** afanasienka@yandex.by

* **Phone:** +375 29 269-87-36

## About me:

I want to start my career in frontend-development and I have already taken several steps to achieve this goal: graduate Yandex.Praktikum frontend-developer course aln self-learned some technologies and frameworks as react and redux.

## Skills:

HTML, CSS (SASS), JS, React, Redux, MobX, BEM, Git

## Code:

#### Task:

Write a function that will find all the anagrams of a word from a list. You will be given two inputs a word and an array with words. You should return an array of all the anagrams or an empty array if there are none. For example:

    anagrams('abba', ['aabb', 'abcd', 'bbaa', 'dada']) => ['aabb', 'bbaa']
    anagrams('racer', ['crazer', 'carer', 'racar', 'caers', 'racer']) => ['carer', 'racer']
    anagrams('laser', ['lazing', 'lazy',  'lacer']) => []

#### Decision

    function anagrams(word, words) {
        const sort = (string) => {
            return string.toLowerCase().split('').sort().join('')
        }
        const model = sort(word)
        return words.filter((el) => {
            return sort(el) === model
        })
    }

## Education: 

2019-2020. Yandex.Praktikum, Front-End developer training course

## Experience:

2021 (4 months): Junior react-developer in Oxios Soft

#### Pet-projects:

TextCounter - simple application that generates dummy text for any app

<https://sasaafanasienka.github.io/Textcounter/>

My own reusable and customizable react-component for creating any carousel block in any app

<https://sasaafanasienka.github.io/Carousel/>

Tetris

<https://sasaafanasienka.github.io/Tetris/>

## English

A2