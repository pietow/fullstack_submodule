fullstack_submodule

### Cloning a Project with Submodules

`git clone --recurse-submodules https://github.com/pietow/fullstack_submodule`
This will also clone the submodules

# OR!!!


`git clone https://github.com/pietow/fullstack_submodule`

The client and server directory are there, but empty.  You must run two commands: git submodule init to initialize your local configuration file, and git submodule update to fetch all the data from that project and check out the appropriate commit listed in your superproject.

``` 
git submodule init
git submodule update
```

# OR!!!

git submodule update --init --recursive

