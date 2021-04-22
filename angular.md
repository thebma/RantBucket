[21/04/2021] - Angular CLI does not provide you with an utility to rename your component generated with `ng generate component <name>`. Angular expects you to sift through many files, rename them, alter *.ts... Just because you made an mistake when you didn't know better. Extreme inconvenient.

Edit 22/04/2021 - It dawned upon me that it would be easier to remove the entire component and recreate it with the desirable name, would be quicker than renaming everything. Albeit bigger components would still be a hassle. Cleaning/removing as outlined here:

[How To Delete A Component In Angular](https://www.angularjswiki.com/angular/how-to-delete-a-component-in-angular/)

[22/04/2021] - Angular router does not support _trivial_ redirection to sub-domains.Let's say I want to redirect from "mywebsite.com" to "assets.mywebsite.com". In no way shape or form is this supported other than hacky solution using `window.location`.

A work around is available, but it does require some work and knowledge, but the article outlines it nicely:

[Using the Angular Router to navigate to external links](https://stackoverflow.com/a/62938120)

