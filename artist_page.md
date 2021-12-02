# How to Create Artists & Artist Pages:
> Edit Artist photos, tour dates, press contacts, roster status, social media links, featured products, email list and more!


<p align="center"><img width=50% height=50% src="views/artist_page.gif"></p>

## Table of Contents 
1. [Getting Started](#getting-started)<br>
    [Create Manually](#create-manually)<br>
    [Import from Spotify](#import-from-spotify)
2. [Editing: Edit View vs Info View](#editing-edit-view-vs-info-view)
3. [Roster Status](#roster-status)
4. [Artist Bio](#artist-bio)
5. [Email List](#email-list)
6. [Tour Dates & Songkick Artist ID](#tour-dates-amp-songkick-artist-id)
7. [Artist Photo](#artist-photo)
8. [Social Media Links](#social-media-links)
9. [Artist Releases](#artist-releases)
10. [Featured Products](#featured-products)

## Getting Started
### Located on the Toolbar Under "Artists":
![](views/toolbar_artist.png)
Or go straight here:  ``/cms/artists``<br />

**Select:``+ Add``** <br />

### Adding an Artist

There's a level of flexibility when deciding how much detail to provide for any given artist. At a minimum, each artist should be created with the following information:

**Name:** Controls how the artist name will be displayed on the live site.<br>
**Sort Name:** Controls how artists will be sorted alphabetically - most band names will be listed the same as Name is noted above. An individual's name should be listed with the last name (surname) first - Rosenstock, Jeff vs American Football. <br>
**URL Alias:** ``/artist_name`` lowercase, replace spaces with underscores: ``/jeff_rosenstock``

There are two ways to add an artist and the above information to CMS:

### Create Manually
    instructions/video
### Import from Spotify 
<p align="center"><img width=50% height=50% src="views/add_new_artist.gif"></p>


## Editing: Edit View vs Info View

Once you've added a new Artist, there are two places to edit Artist content &mdash; the **Edit View** and the **Info View**. 

> **Edit:** Controls elements of both the Artist and Artist Page <br>
> The **edit view** is located by clicking the pencil icon or the "edit" button:
![](views/edit_view.png)

> **Info:** Controls elements of Artist Page Features
> The **info view** is displayed after clicking on the Artist name link once you have created an Artist. In this example above we created an Artists, Julie Byrne, and then clicked the link which was located under the name column.
>![](views/info_view.png)
> Here we can select the "edit button" for edit view, and also access info view to edit featured products, social media links, contacts and other data that is only accessible from this screen:




## Roster Status
Choose between **Active Roster**, **Full Roster**, **Inactive** or **Not On Roster**.

Only Artists that are "Active Roster" will display on the Artists drop down on the Menu bar. This list of artists is also located at ``/artist``.

"Full Roster" Artists are displayed at the bottom of "Active Roster" Artists in the Artist section.

**Example:** To sell products for Artists that are not on your label, you would still add them as an Artist in the CMS, but select "Not On Roster" so they are not displayed on the Artist page or drop down.

## Artist Bio
Add information about the Artist here to be displayed on the Artist page.

## Email List

A “Join Email List” button will display if this artist has a Mailchimp URL and "Has Email List" is checked.

![](views/artist_page_email_list.png)

## Tour Dates & Songkick Artist ID
The Tour section on each Artist page as well as the main Tour section of the website, pulls in tour dates based on the Songkick Artist ID.

In the Artist edit view, you can add "Songkick Artist ID" under **Extra Information**. You can find the artist Songkick Artist ID in the URL of their Songkick page

**Example:** ``https://www.songkick.com/artists/8490418-katy-kirby``. <br>
The Songkick Artist ID is: **8490418**

![](views/songkick_artist_page.png)


For additional help troubleshooting any problems with tour dates displaying &mdash; please see the [Tours](tours.md) section.

## Artist Photo
The Artist photo with the lowest display order will be shown on the Artist page. Only one photo can currently be displayed at a time.
<p align="center"><img width=80% height=80% src="views/artist_photo.png"></p>

## Social Media Links
Social media links will display underneath the Artist photo on the Artist page.
<p align="center"><img width=80% height=80% src="views/social_links.png"></p>

You can edit these pages in the Links tab of the Artist info page:

![](views/artist_page_links.png)

## Artist Releases
Releases may be added to the artist page under the "Artist Page Albums" tab. If there is a product associated with the album this image will be a link to that product.

## Featured Products
These products will be displayed to the right of the Artist photo. We recommend having two products here, they will auto populate with the Artist's best selling products.

![](views/featured_artist_page.png)
