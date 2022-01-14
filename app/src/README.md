# SRC Folder

This is the base code folder, here is the entire application.

## Folder Architecture

```
.
├── __tests__/: Jest global test folder.
├── commons/: Common code that is reusable cross the entire app.
|   ├── components/: Common and base components to reuse across entire app.
|   ├── domain/: Common Business logic (Pure JavaScript/TypeScript)
|   ├── mixins/: Common reusable VueJS mixins.
|   ├── styles/: CSS folder
|   ├── typings/: TypeScript interfaces and types.
|   └── utils/: Helpers or utilities.
|
|
├── layouts/: Contains UI layouts.
├── modules/: Contains isolated app modules.
├── pages/: Nuxtjs file routing system
├── services/: Global HTTP data fetching and management system.
├── static/: Contains files that likely won't be changed.
└── store/: Global state management system (Vuex).
      └── modules/: Global app modules.
```
