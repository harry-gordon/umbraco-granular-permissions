# Umbraco Granular Permissions
An open-source Umbraco package which aims to add granular permissions for things like the Users and Settings sections.

## Notes

This package is still just a twinkle in our collective eyes so please get in touch if you have any ideas or would like to contribute. Here are some of the suggestions we've had so far:

- Sean Thorne suggested [hijacking the tree](https://our.umbraco.com/documentation/extending/section-trees/trees) (via the `TreeNodesRenderingNotification` for example)
- Mike Chambers suggested another approach might be to move the relevant tree node to another Section (e.g. "move LogViewer out of Settings into a custom section that we then let a user via permissions access")
- Matt Wise suggested [this article](http://tooorangey.co.uk/posts/umbraco-v8-variants-and-limiting-editor-access-by-language-an-adventure-story/) as a possibly relevant journey in Umbraco permissions land 

For reference, [here is the Discord discussion](https://discord.com/channels/869656431308189746/882984410432012360/990906690650116136).

## Use-cases

Here are a few use-cases that have been suggested so far:

### Settings section

- Allowing users to just add languages
- Allowing users to see logs

### Users section

- Allowing users to invite users but not edit permissions/delete them/etc
