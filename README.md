Sorry for the Misleading Title. The title should actually be Best Nginx Configuration for PHP Web Application development. Since the title would be too long I just shortened it in this way.

There is nothing called best in this world, it depends on individual person how good they feel about something, likewise, this nginx configuration is what I have in my development machine when I develop PHP applications. I do this way just because I feel lazy to create new Virtual Host for every project, since most of the settings would be same, I thought of making one default configuration file which can serve all of my applications in project folder. This is the reason I would not recommend this settings in Production, Its only for development purpose.

I tried hard to squeeze Nginx to make it more optimized, but the fact is nginx is already a light and highly optimized server, so, there are not much things to optimize.

The configuration looks bit weird as all the files are separated from one another, but this is how I test my configurations, so, I can just add files and comment out the lines that I don't need, this how it'd make me easier to change from one configuration to another for testing.

I will later explain the configuration in details in my Blog.