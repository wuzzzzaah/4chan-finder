4chan-finder
======
**4chan-finder** is a script for searching threads on 4chan from your terminal.

```
Usage: ./4chan-finder [options] <search term>
    -U, --update-cache               Update boards list cache
    -v, --verbose                    Run verbosely
    -b, --board [BOARD NAME]         Board to search
    -i, --interactive                Run in interactive mode
    -h, --help                       Display this screen
```

## TODO
* Make it work
* Make it interactive (Display a small snippet of the OP, the last reply date, and allow the user to choose the thread he wants to access if multiple results are present)
* Implement dump mode (easy)

## Dependencies 
* The xdg gem is necessary for handling config and cache folders location. To install it, enter `[sudo] gem install xdg`.

## Contact
* e-mail: aptyget@gmail.com
* IRC: apt-get on SynIRC and Rizon