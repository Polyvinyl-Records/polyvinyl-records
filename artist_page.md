# How to Create Artists & Artist Pages:
> Create a new artist or edit artist Page photos, tour dates, press contacts, roster status, social media links, featured products, email list and more!<br><br>
> **Quick Start: See [Getting Started](#getting-started) & [Editing: Edit View vs Info View](#editing-edit-view-vs-info-view)**

<p align="center"><img width=50% height=50% src="views/artist_page.gif"></p>


## Table of Contents 
1. [Getting Started](#getting-started)<br>
    - [Create Manually](#create-manually)<br>
    - [Import from Spotify](#import-from-spotify)
2. [Editing: Edit View vs Info View](#editing-edit-view-vs-info-view)
3. [Roster Status](#roster-status)
4. [Artist Bio](#artist-bio)
5. [Email List](#email-list)
6. [Tour Dates & Songkick artist ID](#tour-dates-amp-songkick-artist-id)
7. [artist Photo](#artist-photo)
8. [Social Media Links](#social-media-links)
9. [Artist Releases](#artist-releases)
10. [Featured Products](#featured-products)

## Getting Started
### Located on the Toolbar Under "artists":
![](views/toolbar_artist.png)
Or go straight here:  ``/cms/artists``<br />

**Select:``+ Add``** <br />

### Adding an Artist

There's a level of flexibility when deciding how much detail to provide for any given artist. At a minimum, each artist should be created with a **Name**, **Sort Name** and **URL Alias**. 

- **Name:** Controls how the artist name will be displayed on the live site.<br>
- **Sort Name:** Controls how artists will be sorted alphabetically. Most band names sort name will match their actual name. An individual's name should be listed with the last name (surname) first. **Example:** Rosenstock, Jeff vs American Football. <br>
- **URL Alias:** ``/artist_name`` lowercase, replace spaces with underscores: ``/jeff_rosenstock``
- **[Roster Status](#roster-status)**: Select either Active Roster, Full Roster, Inactive or Not On Roster. Click [here](#roster-status) for a more detailed description. 

You can add the above information **Manually** or using the **Spotify Import** tool: 

- #### Create Manually
    TODO: instructions/video
- #### Import from Spotify 
<p align="center"><img width=50% height=50% src="views/add_new_artist.gif"></p>


## Editing: Edit View &amp; Info View

Once you've added a new artist, there are two places to edit artist content &amp; features &mdash; the **Edit View** and the **Info View**. 

![](views/edit_view.png)

### Edit View
Controls elements of both the artist and artist Page. <br>
The **edit view** is located by clicking the pencil icon or the "edit" button.

### Info View
Controls elements of artist Page Features, such as featured products, social media links, contacts and other data that is only accessible from this screen.<br><br>
The **info view** is displayed after clicking on the artist name link once you have created an artist. In this example below we created an artists, Julie Byrne, and then clicked the link which was located under the name column.

![](views/info_view.png)

## Roster Status
Any artist, band, label, company, or creator can be an "artist" and attached to a product. When creating an artist, choose between the following Roster Status options: **Active Roster**, **Full Roster**, **Inactive** or **Not On Roster**.

Only artists that are **Active Roster** will display on the artists drop down on the Menu bar. This list of artists is also located at ``/artist``.

- **Active Roster**: Will create an artist page, will be searchable on website, will display artist on dropdown menu and at ``/artist.``
- **Full Roster**: Will create an artist page. Will display list of these artists below Active artists on ``/artist`` section and will be searchable on website.
- **Inactive**: Not searchable on website, hidden.
- **Not on Roster**: Searchable on website. 

**Example:** To sell products for artists that are not on your label, you would still add them as an artist in the CMS, but select **Not On Roster** so they are not displayed on the artist page or drop down.

## Artist Bio
Add information about the artist here to be displayed on the artist page.

## Email List

A “Join Email List” button will display if this artist has a Mailchimp URL and "Has Email List" is checked.

![](views/artist_page_email_list.png)

## Tour Dates & Songkick Artist ID
The Tour section on each artist page as well as the main Tour section of the website, pulls in tour dates based on the Songkick Artist ID.

In the artist edit view, you can add "Songkick Artist ID" under **Extra Information**. You can find the artist Songkick Artist ID in the URL of their Songkick page

**Example:** ``https://www.songkick.com/artists/8490418-katy-kirby``. <br>
The Songkick Artist ID is: **8490418**

![](views/songkick_artist_page.png)


For additional help troubleshooting any problems with tour dates displaying &mdash; please see the [Tours](tours.md) section.

## Artist Photo
The artist photo with the lowest display order will be shown on the artist page. Only one photo can currently be displayed at a time.
<p align="center"><img width=80% height=80% src="views/artist_photo.png"></p>

## Social Media Links
Social media links will display underneath the artist photo on the artist page.
<p align="center"><img width=80% height=80% src="views/social_links.png"></p>

You can edit these pages in the Links tab of the artist info page:

![](views/artist_page_links.png)

## Artist Releases
Releases may be added to the artist page under the "artist Page Albums" tab. If there is a product associated with the album this image will be a link to that product.

## Featured Products
These products will be displayed to the right of the artist photo. We recommend having two products here, they will auto populate with the artist's best selling products.

![](views/featured_artist_page.png)
