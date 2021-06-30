# Seppanen Taisto

### Contacts:

- Telegram: [@taisto_seppanen](https://t.me/taisto_seppanen "@taisto_seppanen")
- E-mail: taistopetrseppanen@gmail.com

### About me

I am a junior software developer from the Republic of Karelia,
Russia. I love creating code and do not afraid of any obstacles on
my educational path. Also, I can easily find all necessary
information and apply it for tasks of different complexity. New
technologies don't frighten me, but inspire.
My aim is to become experienced professional, who is able to solve
any issue in a unique and quality manner.

### Skills

- QA & Testing
- Java Core
- HTML
- CSS
- JavaScript
- Git
- Vue.js
- Nuxt.js
- Bootstrap

### Code examples

    import firebase from "firebase/app";

    export async function setNewFilm(newfilm) {
      await firebase
        .database()
        .ref("films/")
        .set({ newfilm });
    }

    export async function getFilms() {
      let filmsArr = [];
      await firebase
        .database()
        .ref("films/")
        .get()
        .then(snapshot => {
          if (snapshot.exists()) {
            filmsArr = snapshot.val().newfilm;
          } else {
            console.warn("bad request");
          }
        });
      return filmsArr;
    }

### Experience

Now i'm working as QA engineer in [Roskavral company](https://roskvartal.ru/o-kompanii)

In 2021 i was complete advanced training courses of modern web development.

- Sipmle [snake game](https://taisto-seppanen.github.io/Snake/ "Snake Game")
- Trainee website for [cinema booking](https://cinimabooking.herokuapp.com/ "cinema booking") with admin page (/login) and database at Firebase

### Education

- 2013 - State Independent Vocational Intitution of Secondary
  Vocational Education of the Republic of Karelia "Motor Transport
  Secondary Technical School" in Petrozavodsk
- 2018 - The Russian Presidential Academy of National Economy and
  Public Administration under the President of the Russian Federation:
  Economics and Finance Faculty.

### English

My english level is A2, but I can easily read documentation and technical literature.
