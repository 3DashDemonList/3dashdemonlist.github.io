          # How to add Records and Levels

Hey, this is a guide written by ~~Mr.Scatman7~~ ME GRUWEL and I will show you how to use the Demonlist Code. 


# How to add Levels

The list is located in **/js/list.js** in that file, you will see the whole list levels and records. I will show you how to add newer levels to the list! 

```javascript

/*=================================================================================*/
		{
			"vids": [
			],
			"name": "Level Name",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "https://www.youtube.com/watch?v=dQw4w9WgXcQ",
                       "key": 0
		},
		/*=================================================================================*/

```

That is the basic template for a level. Now let me go through the stuff real quick.

**name:** This is the Level Name of course
**more:** Just put in none if nobody else helped with the level
**id:** Level ID
**pass:** Level Password
**percentToQualify:** Qualifying Percent
**verificationVid:** Verification Video Link 
**key:** Let me explain this.

0 = #1
1 = #2
2 = #3
so it goes on..

**Verifiers:** If there is a verifier for the level. Just simply add [] after the creator in "author" and put the verifier name in the brackets!

# Adding Records

~~To Add Records you need a Application and use google forms which will work the best in this case. Replace the form links in the **index.html** file.~~ (Ignore this)

```javascript

{
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},

```

That is 1 Record. If you add records you copy and paste them underneath each other. (Not on top)

So if you add a Record it should look like this.

```javascript

/*=================================================================================*/
		{
			"vids": [
        {
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},
			],
			"name": "Level Name",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "Link",
                       "key": 0
		},
		/*=================================================================================*/

```

You see? Not that hard!

# Moving Levels

This should be done correctly or you can break the site. Make sure to do this propperly!

Lets set up 2 Basic Levels with records.

```javascript

/*=================================================================================*/
		{
			"vids": [
        {
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},
			],
			"name": "Level Name",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "Link",
                       "key": 0
		},
		/*=================================================================================*/
		{
			"vids": [
        {
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},
			],
			"name": "Level Name 1",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "Link",
                       "key": 1
		},
    /*=================================================================================*/

```

Now lets move **"Level Name 1"** number 1. And **"Level Name"** to number 2 so we will have to swap them.

Simply Copy And Paste the one you want to bring up or down dose not matter. But I would copy the lower one on top if your moving it up, or if your bringing it down you just copy it and swap or whatever.

```javascript

/*=================================================================================*/
		{
			"vids": [
        {
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},
			],
			"name": "Level Name 1",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "Link",
                       "key": 0
		},
		/*=================================================================================*/
		{
			"vids": [
        {
					"user": "List Username",
					"link": "Link",
					"percent": 100,
					"hz": "120Hz"
				},
			],
			"name": "Level Name",
                       "author": "Level Creator",
                       "more": "none",
                       "id": 0,
                       "pass": "Free to copy",
                       "percentToQualify": 50,
                       "verificationVid": "Link",
                       "key": 1
		},
    /*=================================================================================*/

```

This is the end result that you should be seeing.

# Debugging.

If the site broke, dont worry. There are various ways to fix this!

Just simply click the "Run" button on the Repl. And you should see on the console were the problem is, go to that line and fix the problem!

# Notes

This guide was created by **~~Mr.Scatman7~~ ME GRUWEL** on **2021/01/17**.


Hope this helps!