## Dictionnaire de données pour le bot onboarding

| Nom de la table         | Nom de la colonne                  | Type   | exemple                                | Description                                                  |
| ----------------------- | ---------------------------------- | ------ | -------------------------------------- | ------------------------------------------------------------ |
| Guilds                  | `id_guild`                         | text   | "123456789012345678"                   | Identifiant unique du serveur Discord                        |
| Guilds                  | `name_guild`                       | text   | "simplon serveur hdf"                  | Nom du serrveur Discord                                      |
| Guilds                  | `member_count_guild`               | text   | "100"                                  | Nombre de membres du serveur Discord                         |
| Guilds                  | `configuration`                    | object | "{ welcomeChan: '123', prefix: '!' }"  | Configuration du serveur Discord                             |
| Guilds_templates        | `id_guild_template`                | text   | "123456789012345678"                   | Identifiant unique du template de serveur Discord            |
| Guilds_templates        | `name_guild_template`              | text   | "template simplon"                     | Nom du template de serveur Discord                           |
| Guilds_templates        | `description_guild_template`       | text   | "description template simplon"         | Description du template de serveur Discord                   |
| Members                 | `id_member`                        | text   | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique du membre Discord                         |
| Members                 | `name_member`                      | text   | "Jean Dupont"                          | Surnom discord du membre Discord                             |
| Members_informations    | `id_member_info`                   | text   | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique des informations du membre Discord        |
| Members_informations    | `firstname_member_info`            | text   | "Jean"                                 | Prénom du membre Discord                                     |
| Members_informations    | `lastname_member_info`             | text   | "Dupont"                               | Nom de famille du membre Discord                             |
| Members_informations    | `email_member_info`                | text   | "jean.dupont@example.com"              | Adresse email du membre Discord                              |
| discord_users           | `id_discord`                       | text   | "123456789012345678"                   | Identifiant unique du membre Discord                         |
| discord_users           | `name_discord_user`                | text   | "JeanDupont#1234"                      | Nom d'utilisateur du membre Discord                          |
| discord_users           | `discriminator`                    | text   | "1234"                                 | Discriminant du membre Discord                               |
| identification_requests | `id_identification_request`        | text   | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique de la demande d'identification            |
| identification_requests | `firstname_identification_request` | text   | "Jean"                                 | Prénom de la personne effectuant la demande d'identification |
| identification_requests | `lastname_identification_request`  | text   | "Dupont"                               | Nom de la personne effectuant la demande d'identification    |
| identification_requests | `email_identification_request`     | text   | "jean.dupont@example.com"              | Email de la personne effectuant la demande d'identification  |
| Roles                   | `id_role`                          | text   | "123456789012345678"                   | Identifiant unique du rôle Discord                           |
| Roles                   | `name_role`                        | text   | "cdp"                                  | Nom du rôle Discord                                          |
| Roles                   | `member_count_role`                | text   | "10"                                   | Nombre de membres avec ce rôle Discord                       |
| Roles                   | `position_role`                    | text   | "1"                                    | Position au sein de ce rôle Discord                          |
| Roles                   | `hoist`                            | bool   | true                                   | Si dans une section séparée de la liste des utilisateurs     |
| Roles                   | `color`                            | text   | "#FF0000"                              | Couleur hexadecimale du rôle Discord                         |
| Campuses                | `id_campus`                        | text   | "550e8400-e29b-41d4-a716-446655440000" | Identifiant unique du campus                                 |
| Campuses                | `name_campus`                      | text   | "Valenciennes"                         | Nom du campus                                                |
| Promotions              | `id_promotion`                     | text   | "123456789012345678"                   | Identifiant unique de la promotion                           |
| Promotions              | `name_promotion`                   | text   | "CDA-vals-p4"                          | nom de la promotion                                          |
| Promotions              | `status`                           | text   | "active"                               | Statut de la promotion (active, inactive etc.)               |
| Promotions              | `start_date`                       | date   | "2024-01-01T00:00:00.000Z"             | date de début de la promotion                                |
| Promotions              | `end_date`                         | date   | "2025-12-31T23:59:59.999Z"             | date de fin de la promotion                                  |
| Courses                 | `id_course`                        | text   | "123456789012345678"                   | identifiant unique de la formation                           |
| Courses                 | `name_course`                      | text   | "CDA"                                  | nom de la formation                                          |
| Courses                 | `is_certified`                     | bool   | true                                   | Si la formation est certifiante                              |
| Channels                | `id_channel`                       | text   | "123456789012345678"                   | identifiant unique du channel                                |
| Channels                | `name_channel`                     | text   | "général"                              | nom du channel                                               |
| Channels                | `type`                             | text   | "text"                                 | Type de channel (texte ou vocal)                             |
| Channels                | `position_channel`                 | int    | 1                                      | Positionnement du channel                                    |
| Categories              | `id_category`                      | text   | "123456789012345678"                   | identifiant unique de la catégorie                           |
| Categories              | `name_category`                    | text   | "stock"                                | nom de la catégorie                                          |
| Categories              | `position_category`                | int    | 0                                      | positionnement de la catégorie dans le serveur               |
|                         |                                    |        |                                        |                                                              |
