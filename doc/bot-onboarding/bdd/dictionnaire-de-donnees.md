## Dictionnaire de données pour le bot onboarding

| Nom de la table         | Nom de la colonne             | Type   | Contraintes       | exemple                                | Description                                                  |
| ----------------------- | ----------------------------- | ------ | ----------------- | -------------------------------------- | ------------------------------------------------------------ |
| Guilds                  | `uuid_guild`                  | text   | PK NOT NULL   | "123456789012345678"                   | Identifiant unique du serveur Discord                        |
| Guilds                  | `name_guild`                   | text   | NOT NULL         | "simplon serveur hdf"                  | Nom du serrveur Discord                                     |
| Guilds                  | `member_count_guild`           | text   | NOT NULL         | "100"                                  | Nombre de membres du serveur Discord                        |
| Guilds                  | `configuration`               | object |                   | "{ welcomeChan: '123', prefix: '!' }"  | Configuration du serveur Discord                            |
| Guilds_templates        | `uuid_guild_template`         | text   | PK NOT NULL  | "123456789012345678"                       | Identifiant unique du template de serveur Discord            |
| Guilds_templates        | `name_guild_template`         | text   | NOT NULL          | "template simplon"                     | Nom du template de serveur Discord                          |
| Members                 | `uuid_member`                | text   | PK NOT NULL       | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique du membre Discord                     |
| Members                 | `name_member`              | text   | NOT NULL            | "Jean Dupont"                          | Surnom discord du membre Discord                             |
| Members_informations    | `uuid_member_info`            | text   | PK NOT NULL          | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique des informations du membre Discord        |
| Members_informations    | `firstname_member_informations`| text   | NOT NULL                | "Jean"                                 | Prénom du membre Discord                                     |
| Members_informations    | `lastname_member_informations`| text   | NOT NULL                | "Dupont"                               | Nom de famille du membre Discord                             |
| Members_informations    | `email__member_informations`  | text   | NOT NULL               | "jean.dupont@example.com"              | Adresse email du membre Discord                              |
| discord_users           | `uuid_discord`                | text   | PK NOT NULL     | "123456789012345678"                   | Identifiant unique du membre Discord                         |
| discord_users           | `discord_user_name`           | text   | NOT NULL              | "JeanDupont#1234"                      | Nom d'utilisateur du membre Discord                          |
| discord_users           | `discriminator`               | text   | NOT NULL         | "1234"                                 | Discriminant du membre Discord                               |
| identification_requests | `uuid_identification_request` | text   | PK NOT NULL      | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique de la demande d'identification            |
| identification_requests | `firstname_identification_request`| text   | NOT NULL           | "Jean"                                 | Prénom de la personne effectuant la demande d'identification |
| identification_requests | `lastname_identification_request`| text   | NOT NULL           | "Dupont"                               | Nom de la personne effectuant la demande d'identification    |
| identification_requests | `email_identification_request`| text   | NOT NULL          | "jean.dupont@example.com"              | Email de la personne effectuant la demande d'identification  |
| Roles                   | `uuid_role`                   | text   | PK NOT NULL     | "123456789012345678"                   | Identifiant unique du rôle Discord                           |
| Roles                   | `name_role`                   | text   | NOT NULL              | "cdp"                                  | Nom du rôle Discord                                          |
| Roles                   | `member_count_role`           | text   | NOT NULL                | "10"                                   | Nombre de membres avec ce rôle Discord                       |
| Roles                   | `position_role`               | text   | NOT NULL                | "1"                                    | Position au sein de ce rôle Discord                          |
| Roles                   | `hoist`                       | bool   | NOT NULL                  | true                                   | Si dans une section séparée de la liste des utilisateurs     |
| Roles                   | `color`                       | text   | NOT NULL                | "#FF0000"                              | Couleur hexadecimale du rôle Discord                         |
| Campuses                | `uuid_campus`                 | text   | PK NOT NULL      | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique du campus                                 |
| Campuses                | `name_campus`                 | text   | NOT NULL               | "Valenciennes"                         | Nom du campus                                                |
| Promotions              | `uuid_promotion`              | text   | PK NOT NULL     | "123456789012345678"                   | Identifiant unique de la promotion                           |
| Promotions              | `name_promation`              | text   | NOT NULL               | "CDA-vals-p4"                          | nom de la promotion                                          |
| Promotions              | `is_active`                   | bool   | NOT NULL                   | true                                   | Si la promotion est active                                   |
| Promotions              | `start_date`                  | date   | NOT NULL                  | "2024-01-01T00:00:00.000Z"             | date de début de la promotion                                |
| Promotions              | `end_date`                    | date   | NOT NULL                  | "2025-12-31T23:59:59.999Z"             | date de fin de la promotion                                  |
| Courses                 | `uuid_courses`                | text   | PK NOT NULL     | "123456789012345678"                   | identifiant unique de la formation                           |
| Courses                 | `name_course`                 | text   | NOT NULL              | "CDA"                                  | nom de la formation                                          |
| Courses                 | `is_certified`                | bool   | NOT NULL          | true                                   | Si la formation est certifiante                              |
| Channels                | `uuid_channel`                | text   | PK NOT NULL     | "123456789012345678"                   | identifiant unique du channel                                |
| Channels                | `name_channel`                | text   | NOT NULL        | "général"                              | nom du channel                                               |
| Channels                | `type`                        | text   | NOT NULL | "text"                                 | Type de channel (texte ou vocal)                             |
| Channels                | `position_channel`            | int    |  NOT NULL                 | 1                                      | Positionnement du channel                                    |
| Categories              | `uuid_category`               | text   | PK NOT NULL     | "123456789012345678"                   | identifiant unique de la catégorie                           |
| Categories              | `name_category`               | text   | NOT NULL                | "stock"                                | nom de la catégorie                                          |
| Categories              | `category_position`           | int    | NOT NULL                 | 0                                      | positionnement de la catégorie dans le serveur               |
|                         |                               |        |                   |                                        |                                                              |
