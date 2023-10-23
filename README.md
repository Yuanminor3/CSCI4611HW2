Name: N/A

Third Party Assets: N/A

Wizard Functionality: N/A

I believe I fulfill all the requirements of canvas instruction. At the start of the game, individual spheres of different sizes are generated along with randomized speeds. 
Winning the game requires getting smaller objects first to make the hole large enough to get the larger objects.

Note: Very rarely there will be a case where a large sphere will block a smaller one after stopping move, causing us to possibly not see it while playing the game. But this is a very rare occurrence. Since I set the speed to random, this may still happen even though I controlled the speed/size parameters as much as possible. In this case, if we can't find a sphere of the right size, we try to guess and find as much as we can that a small sphere is behind some larger ones.