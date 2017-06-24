# Project 2 - *Flix*

**Flix** is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Time spent: **15** hours spent in total

## User Stories

The following **required** functionality is complete:

- [X ] User can view a list of movies currently playing in theaters from The Movie Database.
- [X ] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [X ] User sees a loading state while waiting for the movies API.
- [X ] User can pull to refresh the movie list.

The following **optional** features are implemented:

- [X ] User sees an error message when there's a networking error.
- [X ] Movies are displayed using a CollectionView instead of a TableView.
- [ X] User can search for a movie.
- [ ] All images fade in as they are loading.
- [ ] User can view the large movie poster by tapping on a cell.
- [ ] For the large poster, load the low resolution image first and then switch to the high resolution image when complete.
- [ ] Customize the selection effect of the cell.
- [ ] Customize the navigation bar.
- [ ] Customize the UI.

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. I think it would be cool to have an extension so that when you click on the movie it links you to nearby theaters that are playing it. This would definitely be an extensive addition though. 
2. Another area I would like to further explore is adding a favorites or a bookmarks page. I think this would actually be a vialble addition that we could do. We would have some sort of push from each movie on the details page that links to another view controller that stores all of the "liked" or "saved" movies for the user. 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src=http://imgur.com/lemvJv2 title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

There were many many challenges while writing this app. I think the one I struggled with most though was figuring out how to add an alert when there's a networking error. Having the alert pop up was not the hard part though, it was figuring out how to keepn it there if the network was still unconnected and how to make it dissapear if the the wifi suddenly reconnected. I think this issue was one of the hardest becuase it required that I restructure my entire code to make it so that I am able to reload the data when I hit the "try again" button. However, I do think that this is a testament to the importance of style in coding. I did not realize how disorganized and messy my code was until I tried to move things around and was lost in my own code.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library

## License

    Copyright [Elan Halpern]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
