# Hey there! <br />

```c
#include <stdio.h>
#include <time.h>

typedef struct {
    char name[50];
    int age;
    char hobbies[100];
    char current_role[50];
} SoftwareDeveloper;

SoftwareDeveloper software_developer() {
    SoftwareDeveloper me;

    snprintf(me.name, sizeof(me.name), "Thalys Leite");

    time_t now = time(NULL);
    struct tm *t = localtime(&now);
    int current_year = t->tm_year + 1900;
    me.age = current_year - 2000;

    snprintf(me.hobbies, sizeof(me.hobbies), "Travel to incredible (or not so incredible) places.");

    snprintf(me.current_role, sizeof(me.current_role), "Software Developer");

    return me;
}

int main() {
    SoftwareDeveloper me = software_developer();

    printf("Name: %s\n", me.name);
    printf("Age: %d\n", me.age);
    printf("Hobbies: %s\n", me.hobbies);
    printf("Current Role: %s\n", me.current_role);

    return 0;
}

```

## ✨ Technologies

**Frontend stack:**

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Styled components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)

**Backend stack:**

![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Fastify](https://img.shields.io/badge/fastify-202020?style=for-the-badge&logo=fastify&logoColor=white)

**Databases:**  

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

**DevOps & Cloud:**

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

**Languages:**

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
