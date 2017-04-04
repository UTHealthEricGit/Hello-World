# Hello-World
The very first time - Just another repository
Hi Humans!
The lex, coupes, bimaz & the benz.
To all of my peeps in the world, keep your head up.
So the SID really does matter. Prior to taking your clone or image, just remember to use Sysprep as follows:

1) Run Sysprep (on Windows Server 2008 this is located in c:\Windows\System32\Sysprep\Sysprep.exe)
2) Ensure ‘System Out-of-Box Experience (OOBE)’ is selected
3) Tick the ‘Generalize’ option (this resets the SID)
4) Select ‘Shutdown’ from the Shutdown Options.
5) Once the machine has shutdown, take your image and you are good to go!

If Cloning through vSphere, clone pocess will perform SysPrep for you, just remember to select option to do that.

In case you are wondering, some of the things that have to be unique for each computer include:

1)The Windows Security Identifiers (SIDs)
2)The Media Access Control (MAC) address
3)The Internet Protocol (IP) address
4)The NetBIOS and Fully Qualified Domain (FQDN) names
