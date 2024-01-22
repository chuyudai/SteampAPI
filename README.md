# STEAMPY

STEAM API wrapper based on steamapis

## Installation

```bash
$ pip install steampy
```

## User's guide for steampy

A User's guide including how to install and set up, how to use each function in the packages including guide for choosing function parameters can be found here:  [Steampy user's guide](../steampy/steampy%20user's%20guide.ipynb)


## Functionality

- **Visualize** API game coverage and steam purchase/tranaction information.
- Retrieve information on specific user's profile.
- Retrieve information on specific user's profile inventory.
- Generate **dataframe** and **report style** paragraph for interested games.

    Report example: 
    
     > 'Beholder' was released on Nov 9, 2016. The game was developed by ['Warm Lamp Games'] and published by ['Alawar Premium']. 

     > *Description of the game*: You’re a state-installed landlord in a totalitarian country. Place listening devices, steal and sneak into your tenants’ apartments. Use what you uncovered to report anyone capable of plotting against the state. You MUST! But WILL you?.

     > Beholder is recommended by 12503 number of people. The game costs 9.99 USD.

     > It is available on Linux, Mac, Windows.
    
- **Ambigious search**  
    The function is enabled by the use of **regular expression** and help user find games that they only have vague memory about. 
    The function allow user to input whatever they remembered for the game name, and will return a dataframe and a report for users with all matched games on steam.
- Retrieve top discounted game by recommendation
- Retrieve information on free games.


## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`steampy` was created by Chuyu Dai. It is licensed under the terms of the MIT license.

## Credits

`steampy` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
