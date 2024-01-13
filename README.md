
# IMDB Clone

It is IMDB clone project.

In this project we can search different movies and we are also able to add them to our favouriate/watchlist for future refferences.

We can search different movie by typing their name in the search bar.

When we mark any particular movie as favouriate than it is added to our watchlist and gets stored in the localstorage of the browser so that it does not disappear when we refresh the page.

This project uses an api named as OMDB and fetches all movies from there only.

It has three different pages one for the home page to display main section of the project, one for details of the movie which shows some of the details of the movie and one is for watchlist which contains all the movies which we had marked as favouriate/watchlater.

Main page shows all the movies which come after search.

Movie details page shows some of the information about the particular movie.

Watch list page shows all the movies which are marked as favouriate with some information about them.
## Languages Used
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

For making different pages and the basic structure of the project like search bar, add to watchlist icon, delete icon, home page, movie details page and favouriate page etc.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

Used for the basic and good looking styling of the project so that the project looks good and appealing.

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

To implement all the functionalities of the project like fetching data from api, displaying movies based on search bar input value, saving favouriate movies to localstorage, fetching from localstorage to display them in watchlist page.
## Deployment

I had hosted the project live on -
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)

[Hosted Link](https://sage-elf-5c4960.netlify.app)


## E-mail Address

[![MIT gmeil](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://choosealicense.com/licenses/mit/)

[My Gmail ID](ramavtarnagar13@gmail.com)





## 🔗 My Socials

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white) 

https://www.linkedin.com/in/ramavtar-nagar-a942a4216?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)

https://x.com/Ramavta60509861?t=7nTCY6zozQfNJs5uYGFyTQ&s=09




## API Reference

#### Get all items

```http
  GET /api/items
```

| API Key | Type     | API Address                |
| :-------- | :------- | :------------------------- |
| `48aa722f` | `string` | https://www.omdbapi.com/ |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | https://www.omdbapi.com/?i=${id}&apikey=${key} |


