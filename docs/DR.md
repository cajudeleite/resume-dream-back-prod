### Main
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/` | `landing_page` | `GET` | `src\Controller\Api\V1\MainController` |  `landingPage` |
| `/api/v1/inscription` | `register` | `POST` | `src\Controller\Api\V1\MainController` |`register`|

### CONNEXION
| `/api/v1/login` | `login` | `POST` | `src\Controller\Api\V1\SecurityController` |  `login` |


### PERSONAL AREA
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace` | `mon_espace` | `GET` | `src\Controller\Api\V1\HomeController` |`browse`|  

### PROFIL
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
|`/api/v1/mon-espace/profil/user/read`| `user_read` | `GET` | `src\Controller\Api\V1\ProfileController` |`read`| 
|`/api/v1/mon-espace/profil/user/edit`| `user_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\ProfileController`|`edit`| 


### EXPERIENCES
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/experience` | `experience_browse` | `GET` | `src\Controller\Api\V1\ExperienceController` |`browse`| 
| `/api/v1/mon-espace/profil/experience/{id}` | `experience_read` | `GET` | `src\Controller\Api\V1\ExperienceController` |`read`| 
| `/api/v1/mon-espace/profil/experience/{id}` | `experience_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\ExperienceController`|`edit`| 
| `/api/v1/mon-espace/profil/experience` | `experience_add` | `POST` | `src\Controller\Api\V1\ExperienceController` |`add`| 
| `/api/v1/mon-espace/profil/experience/{id}` | `experience_delete` | `DELETE` | `src\Controller\Api\V1\ExperienceController` |`delete`| 

### SKILLS
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/competences` | `skill_browse` | `GET` | `src\Controller\Api\V1\SkillController` |`browse`| 
| `/api/v1/mon-espace/profil/competences/{id}` | `skill_read` | `GET` | `src\Controller\Api\V1\SkillController` |`read`| 
| `/api/v1/mon-espace/profil/competences/{id}` | `skill_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\SkillController`|`edit`| 
| `/api/v1/mon-espace/profil/competences` | `skill_add` | `POST` | `src\Controller\Api\V1\SkillController` |`add`| 
| `/api/v1/mon-espace/profil/competences/{id}` | `skill_delete` | `DELETE` | `src\Controller\Api\V1\SkillController` |`delete`| 

### EDUCATIONS
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/formation` | `education_browse` | `GET` | `src\Controller\Api\V1\EducationController` |`browse`| 
| `/api/v1/mon-espace/profil/formation/{id}` | `education_read` | `GET` | `src\Controller\Api\V1\EducationController` |`read`| 
| `/api/v1/mon-espace/profil/formation/{id}` | `education_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\EducationController`|`edit`| 
| `/api/v1/mon-espace/profil/formation` | `education_add` | `POST` | `src\Controller\Api\V1\EducationController` |`add`| 
| `/api/v1/mon-espace/profil/formation/{id}` | `education_delete` | `DELETE` | `src\Controller\Api\V1\EducationController` |`delete`| 

### ACTIVITIES
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/activite` | `activity_browse` | `GET` | `src\Controller\Api\V1\ActivityController` |`browse`| 
| `/api/v1/mon-espace/profil/activite/{id}` | `activity_read` | `GET` | `src\Controller\Api\V1\ActivityController` |`read`| 
| `/api/v1/mon-espace/profil/activite/{id}` | `activity_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\ActivityController`|`edit`| 
| `/api/v1/mon-espace/profil/activite` | `activity_add` | `POST` | `src\Controller\Api\V1\ActivityController` |`add`| 
| `/api/v1/mon-espace/profil/activite/{id}` | `activity_delete` | `DELETE` | `src\Controller\Api\V1\ActivityController` |`delete`| 

### LANGUAGES
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/langue` | `language_browse` | `GET` | `src\Controller\Api\V1\LanguageController` |`browse`| 
| `/api/v1/mon-espace/profil/langue/{id}` | `language_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\LanguageController`|`edit`| 
| `/api/v1/mon-espace/profil/langue` | `language_add` | `POST` | `src\Controller\Api\V1\LanguageController` |`add`| 
| `/api/v1/mon-espace/profil/langue/{id}` | `language_delete` | `DELETE` | `src\Controller\Api\V1\LanguageController` |`delete`|

### SOCIAL_NETWORK
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/profil/reseaux-sociaux` | `social_network_browse` | `GET` | `src\Controller\Api\V1\SocialNetworkController` |`browse`| 
| `/api/v1/mon-espace/profil/reseaux-sociaux/{id}` | `social_network_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\SocialNetworkController`|`edit`| 
| `/api/v1/mon-espace/profil/reseaux-sociaux` | `social_network_add` | `POST` | `src\Controller\Api\V1\SocialNetworkController` |`add`| 
| `/api/v1/mon-espace/profil/reseaux-sociaux/{id}` | `social_network_delete` | `DELETE` | `src\Controller\Api\V1\SocialNetworkController` |`delete`| 


### PERSONAL DATA
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--| 
| `/api/v1/mon-espace/profil/donnees-personelles/{id}` | `personal_data_read` | `GET` | `src\Controller\Api\V1\PersonalDataController` |`read`| 
| `/api/v1/mon-espace/profil/donnees-personelles/{id}` | `personal_data_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\PersonalDataController`|`edit`| 
| `/api/v1/mon-espace/profil/donnees-personelles` | `personal_data_add` | `POST` | `src\Controller\Api\V1\PersonalDataController` |`add`| 
| `/api/v1/mon-espace/profil/donnees-personelles/{id}` | `personal_data_delete` | `DELETE` | `src\Controller\Api\V1\PersonalDataController` |`delete`|


### CV
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/api/v1/mon-espace/mes-cv` | `cv_browse` | `GET` | `src\Controller\Api\V1\CvController` |`browse`| 
| `/api/v1/mon-espace/mes-cv/{id}` | `cv_read` | `GET` | `src\Controller\Api\V1\CvController` |`read`| 
| `/api/v1/mon-espace/mes-cv/{id}` | `cv_edit` | `PUT` `PATCH` | `src\Controller\Api\V1\CvController`|`edit`| 
| `/api/v1/mon-espace/mes-cv` | `cv_add` | `POST` | `src\Controller\Api\V1\CvController` |`add`| 
| `/api/v1/mon-espace/mes-cv/{id}` | `cv_delete` | `DELETE` | `src\Controller\Api\V1\CvController` |`delete`|

### USER
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/admin/user` | `user_browse` | `GET` | `src\Controller\Back\UserController` |`browse`| 
| `/admin/user/{id}` | `user_read` | `GET` | `src\Controller\Back\UserController` |`read`| 
| `/admin/user/{id}` | `user_edit` | `PUT` `PATCH` | `src\Controller\Back\userController`|`edit`| 
| `/admin/user/{id}` | `user_delete` | `DELETE` | `src\Controller\Back\UserController` |`delete`| 

### TEMPLATE
| Routes | Nom de la route | Méthode HTTP | Controller | ->méthode() |
|--|--|--|--|--|
| `/admin/template` | `template_browse` | `GET` | `src\Controller\Back\TemplateController` |`browse`| 
| `/admin/template/{id}` | `template_edit` | `PUT` `PATCH` | `src\Controller\Back\TemplateController`|`edit`| 
| `/admin/template` | `template_add` | `POST` | `src\Controller\Back\TemplateController` |`add`| 
| `/admin/template/{id}` | `template_delete` | `DELETE` | `src\Controller\Back\TemplateController` |`delete`| 
