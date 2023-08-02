# React Folder Structure - How To Organize React Projects

## Table of contents

- [React Folder Structure - How To Organize React Projects](#react-folder-structure---how-to-organize-react-projects)
  - [Table of contents](#table-of-contents)
  - [2. Intermediate](#2-intermediate)
    - [2.1. assets folder](#21-assets-folder)
    - [2.2. context folder](#22-context-folder)
    - [2.3. data folder](#23-data-folder)
    - [2.4. hooks folder](#24-hooks-folder)
    - [2.5. utils folder](#25-utils-folder)
    - [2.6. components folder](#26-components-folder)
    - [2.7. pages folder](#27-pages-folder)
    - [3. Advanced](#3-advanced)
    - [3.1. pages folder](#31-pages-folder)
    - [3.2. layouts folder](#32-layouts-folder)
    - [3.3. lib folder](#33-lib-folder)
    - [3.4. services folder](#34-services-folder)
    - [3.5. features folder](#35-features-folder)

## 2. Intermediate

![](./images/int_all.JPG)

### 2.1. assets folder

![](./images/int_assets.JPG)

Contain any type of assets that you import to use in your code, things like _images_, _svg files_, _global CSS_ ...

### 2.2. context folder

![](./images/int_context.JPG)

Contain all the contexts you create.

### 2.3. data folder

![](./images/int_data.JPG)

Contain any json data you have or constant values file ...

### 2.4. hooks folder

![](./images/int_hooks.JPG)

Contain all the hooks you create.

### 2.5. utils folder

![](./images/int_utils.JPG)

Contain small and simple functions (no matter what input you gave it, it always gave you the same output and it doesn't have any weird side effect) that you use in your project.

### 2.6. components folder

![](./images/int_components.JPG)

Contain all the components you use in your pages.

![](./images/int_comp_form.JPG)

The `form` subfolder contain your form components.

![](./images/int_comp_ui.JPG)

The `ui` subfolder contain your form components.

### 2.7. pages folder

![](./images/int_pages.JPG)

Contain many folders, every one is for a specific page of the application.

![](./images/int_pages_home.JPG)

Every page folder contain components that are unique for the specific page (not shared between many pages).

### 3. Advanced

It's the Intermediate version + some changes & additional folders

![](./images/adv_all.JPG)

### 3.1. pages folder

![](./images/adv_pages.JPG)

We no longer have folders, we just have individual files for each of our pages.

### 3.2. layouts folder

![](./images/adv_layouts.JPG)

Specific for components that deals with links like `Navebar`, `Sidebar` and `Footer`.

### 3.3. lib folder

![](./images/adv_lib.JPG)

It's an implementation of the Facade Pattern. For example you use the `axios` library, so you wrap it in your own code.

### 3.4. services folder

![](./images/adv_services.JPG)

Contain all the services for calling your api.

### 3.5. features folder

![](./images/adv_features.JPG)

Contain many folders, every one is for a specific feature of the application.

![](./images/adv_feat_auth.JPG)

![](./images/adv_feat_sett.JPG)

![](./images/adv_feat_todos.JPG)

Every feature folder contain all the code for the specific feature, it's a mini version of the `src` folder the feature.

The `index.js` file is used to export all the things we went to use from the feature, and then we only import it from this `index.js` file.
