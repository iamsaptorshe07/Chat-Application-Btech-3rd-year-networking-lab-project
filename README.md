#### Usage:

Execute the below from Windows command prompt/Linux Shell[**](#footnote)
1. Test to make sure you have all the required dependencies at place. Typing
   ``
   python3 -m tkinter
   ``
   should not error out. If it does, you have missing Tkinter module,
   which needs to be installed.
2. Now, first start the server from [multiChatServer.py](multiChatServer.py)
   ```
   python3 multiChatServer.py
   ```
3. Then, run the below to start one client from [multiChatClient.py](multiChatClient.py):
   ```
   python3 multiChatClient.py
   ```
   If you need more than one client, run the above command on seperate command windows. 

#### System Requirements :
 * Python 3.6 or greater
 * Threading (inbuild in Python Standard Library)
 * Sockets (inbuild in Python Standard Library)

<a name="footnote">
**Build on __WINDOWS 7__. Tested on __Windows__ and __Linux__ also.
</a>