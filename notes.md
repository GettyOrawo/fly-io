**So Fly**

**what I built**

- I built a user friendly interface for the deployment details
It's easy to identify state using **different colors** without necessarily reading out the texts. So I used the various **text colors and icons/emojis** to display a successful/pending/failed deployment status. The most important details in my opinion was knowing is the deploy was successful or not through an icon status and a short description of the same

- When it comes to the instances, I used a **diagram representation** of the instances for the user to take a quick glimpse at the counts and know the status of the instances. Added the total instances for us to know how many instances are available up front.
I then went ahead to **list each** of these instances while paying attention to the **health checks** because this is usually the first information that we look for. 

- There is a **```more about instance```** button that pops up a display of every other information about that instance in one click. In the future, if there was any additional information about an instance that may not be as important to see on first contact, this is where we'll place it.

**what I didn't build and would improve or fix if I had more time**

- I was thinking of doing a filter on instances, where a user can list only the passing/failing instances or ones whose tasks are workers and more. At this point they are limited to searching through every instance.

- Also whenever there is a failing instance, I feel we should give more information on where this fail could be coming from(maybe suggestions), even if it means redirecting the users to the troubleshooting docs

- I found it important to also place the date and time on the list of instances for accountability. If the instances were created today or yesterday they could as well just read ```today 10:42 p.m```or ```yesterday 11:57 a.m``` any day before yesterday can be placed in a more readable format such as ```Wed 24th May 2021 9:17 a.m```

- The code, definitely needs a lot of work

**how I'd determine if this feature is successful**

- I would determine this if viewing the interface I created makes it more easier for me or anyone else to know details about the deployment alongside the instances than running ```flyctl status``` . This command is amazing and has quite a lot of details to take in , so the whole point is placing it in a reasonable manner that anyone, irregardless of experience levels when it comes to deployment, would understand what's going on at first glance. The simpler, the better.

Above all, I had so much fun doing this!