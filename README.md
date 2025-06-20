# Google-Bug-discovery
I was testing meta prompts to test system capabilities when I accidentally discovered this bug.
The conditions were like this:
174,000 context of long and complex discussion of AI behavior and meta commentary on itself.
On top of that I put the AI into a real world scenario to test the difference in its output compared to when it was giving the advice on the problem.
This according to me, caused the platform itself to justify that the current query and the long and complex context could not be answered by the current model and directed it to an internal model(Kingfall) and gave me this error models/kingfall-ab-test is not found for API version v1main, or is not supported for generateContent. Call ListModels to see the list of available models and their supported methods.This potentially sounds like an internal routing error but I am speculating since I am not Google's Safety Team. This might be the one which was active for 20 minutes and google took down but I could be wrong. I reported this to Google's VRP program and they classified it as a prompt injection when it wasn't but that's my opinion.
