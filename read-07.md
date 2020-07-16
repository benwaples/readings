## Reading 06 summary

## History of local storage
This is a really good article. I like seeing how the need for local storage came about and how to use it... however I don't understand the code snippets throughout the article. I feel like I get the description of each snippet, but then they show the code and it just doesn't make sense to me.

Each page has 5mg of storage... that doesn't seem like much? But because the data is stored in JSON format, it saves space (cause everything is a string and computers treat strings like the middle child -- they clearly have something going on but they choose to just let it be). Also the code example for getting and setting format, they don't stringify -> parse the data, they just send it to localStorage and then get it and treat it as a string... normal? idk. 

Sounds like localStorage could be replaced with something more simple that is scalable for memory size! Maybe it's been released now that it's been 9 years since the writing of this article.