<style>
    h1, h2, h3, h4, h5, h6 {
        border: none;
        margin-bottom: 1ch;
    }

    h2 {
        margin-bottom: .25ch;
    }
    
    p {
        color: lime;
    }
</style>

# Commands

## go into enable mode
switch\> enable

## go into configuration mode
switch\# configure terminal

## set switch name
switch(config)# hostname [name]

## set username for the enable mode
name(config)# username [name]

## set enable password
name(config)# enable password [password]

## set secret password
name(config)# enable secret [password]

## set banner for unauthorized login
name(config)# banner motd [message]

## set ssh passwords
name(config)# line vty [start-port] [end-port]
