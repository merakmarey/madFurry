# madFurry
madFurry - a madMax plotter GUI (v0.1 for madMax plotter v 1.1.7)

madFurry is a Windows Forms application oriented to provide a more usable user interface for the madMax chia plotter.

Features

- System information and suggestions for plotting.

Along with the info/status about the system available resources, suggestions will be provided for the amount of threads depending on available resources and other parameters, such as processor core count, space available and simultaneous plotting processes.

- Multiple final destinations.

You can add multiple final destinations, madFurry will alternate the final destination for each plotting process to distribuite the competed plots among all the destinations on the list.

- Continuos mode

madFurry will re-start a plotting task with a brand new, fresh plotting task process after recycling all the resources previously used by the completed task. Each time a plotting task is restared will create a new process to avoid any issues associated with long running processes.

- Copy to destination on a separated task.

If checked, after plotting is completed, the task will conclude (or restart, if continuous mode is selected) without waiting for moving the file to the final directory. The file moving will be executed asynchronously on a separated task, allowing the original task to comclude or restart without delay. If not checked moving the file will be done by the madMax plotter adding time to the completion of the process (-d option). 

- Use internal Ultra Fast Copy function.

If checked, the plot will be moved with an internal enhanced file feature, otherwise a regular Windows copy will move the file.

- Extra improvements

There are some tweaks and hacks to improve stability AND performance of the plotter process AND the files I/O. Also, since each plot is created by a single process and after that the process and its resources get recycled, there is no risk for any issues with long running processes.

- Why is this better than any other plotter manager based on powershell or CLI's?

As I said, the hacks. There is a lot PowerShell simply cannot do, and even the madMax plotter don't have. The Ultra Fast Copy function is around 20% faster than the madMax file copy. Do some benchmarking, plot using cmd line and then plot using madFurry, let me know your results on my discord @ https://discord.gg/V2x9MSpCFe

- Future development.

Logging, statistics, configuration files, auto-restarts, alerts via text msg/email, a more intelligent plot distribuition system, and a secret plan regarding RAM plotting. A Linux version maybe?

- Why not publishing the source code?

I am, like any other human being, a little selfish, so I'll keep the source code..FOR NOW..BUT I WILL EVENTUALLY PUBLISH IT ALL.  The main reason for this? I don't want maFurry code to be used with a malicious purpose, and as now it will be quite easy to do so...So, if anyone wants to steal your crypto or info, it should come with something better than madFurry. There is another option though. If Max, any Chia DEVS like Justin England, or anyone from the CHIA NETWORK or any Youtuber with a dedicated channel and technical programming knowledge (like  Sloth Tech TV or others) wants to audit my code I am more than willing to show all and even make a vid about it. ha? haaa??!!  

- Why should I trust you and your software?.

YOU SHOULD'NT. Not mine or anyone. ALWAYS take precautions. See https://www.youtube.com/watch?v=n0P9FO1DafM for a better understanding and best practices to keep you chia or any other crypo assests secured. That being said, I am NOT gonna steal ANYTHING from you. I have been a software engineer for many many years and I prefer to make my money working.
Here's my linkedin profile https://www.linkedin.com/in/merakmarey/ if you want to insult me. :)

But if you like this project and want to support it, here's how. Buy me a beer!..I mean..I need this to buy hardware and do further testing...

XCH : xch109mlsnkddjea68m5vxpzerf64cav4prhvrkf0hqxz9wfxhpcluasgjfr6r

ETH : 0xCd7B9801e63627D12D6abA45dC2688B25E3A2e54

BTC : bc1q4fvt2lxsnsdg36rqced65s5jwntvcph7nutlk7

Tether USD : 0xCd7B9801e63627D12D6abA45dC2688B25E3A2e54

XRP : rEW6Y1cW3vi2fG4gLqxLBwxnSktFndRTL9

Dogecoin : DS3qkyuCHaz8eTdvpiw9Tn6Q4XojJGSaFL




