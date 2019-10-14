## Compiling

**Note:** _Do NOT download or compile as the root user._

#### Download the dependencies required to build Fuzion:

If you are having problems compiling make sure you've got the latest version of `g++`.

```bash
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get install gcc-9 g++-9
sudo update-alternatives --config gcc
sudo update-alternatives --config g++
```

==================

__Ubuntu:__
```bash
sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev patchelf
```

===================

#### Download Fuzion:

```bash
git clone --recursive https://github.com/hollowmangiggs/Fuzion
```

```bash
cd Fuzion
```

===================

#### Compile with build script

You can build easily with the included build script.
```bash
./build
```

You can later update with 
```bash
./update
```


## Injecting using the load script

First of all, make sure CS:GO is open, it does not matter whether you are in game or not. However, it is not recommended to inject while CS:GO is loading into a map. 

Navigate to the directory where Fuzion was built if you have not ready.
```bash
cd Fuzion
```

Now, you can inject the hack with the `load` script
```bash
./load
```

You might be prompted to enter in your password, this is because the injection script requires root access.

The text printed out during injection is not important. 

If the injection was successful you will see a message at the bottom saying `Successfully injected!`, however, if the message says `Injection failed`, then you've most likely done something wrong.

Now, go back into CS:GO, if you are in the main menu of the game you should see a banner in the top left like so:

![this](http://i.imgur.com/Gb0SV1u.png)

*Note:* if you are getting crashes ( that are unrelated to game updates ) Try disabling shader precaching in your Steam Client -> Steam -> Settngs -> Shader Pre-Caching. 

## Using the hack

Now that Fuzion has been injected into the game, press <kbd>Insert</kbd> on your keyboard to open the hack menu (<kbd>ALT</kbd>+<kbd>I</kbd> if you are using a laptop).

If you want to change skins, create and load configs or open the player list, you can find those buttons at the top of the screen.


## Unloading the hack

If you wish to unload the hack from the game, you can do so by entering the command:
```bash
./uload
```
or type 'exit' you dickhead!
