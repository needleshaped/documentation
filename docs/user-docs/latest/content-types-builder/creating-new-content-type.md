# Creating content types

Strapi allows to create 2 main content types using the Content-Types Builder: collection types and single types.

- Collection types are content types that can be reused several times.
- Single types are content types that are created for one purpose and are meant to be used once.

Through the Content-Types Builder, it is also possible to create components, although they are not proper content types as they cannot exist indepentely. Components are a combination of fields that can be used as a group when configuring the fields of a content type.

## Creating a new content type

Content types are created from the Collection types and Single types categories of the Content-Types Builder navigation.

To create a new content type:

1. Choose whether you want to create a collection type or a single type.
2. Click on the **Create a new collection/single type** button in the category of the content type you want to create.
3. In the content type creation window, write the name of the new content type in the *Display name* textbox. In creating a collection type, opt for a singular name, as collection type names are automatically pluralised when displayed in the Content Manager.
4. (optional) In the Advanced Settings tab, configure the available settings for the new content type:

| Setting name    | Instructions                                                                                                                                     |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| Draft & Publish | Click on **ON** to activate the Draft & Publish feature for your content type (see Draft & Publish). Click on **OFF** to deactivate the feature. |
| Collection name | Write a collection name for your content type.                                                                                                   |

5. Click on the **Continue** button.

After these steps, your new content type is created and should be displayed in the list of collection or single types, in the Content-Types Builder. It however needs to be configured with fields to be saved and made ready for use (see Adding and configuring fields).

## Creating a new component

Components are created from the same-named category of the Content-Types Builder navigation.

To create a new component:

1. Click on the **Create a new component** button.
2. In the component creation window, configure the base settings of the new component:
   - Write the name of the component in the *Name* textbox.
   - Select an available category, or enter in the textbox a new category name to create one.
   - Choose an icon to represent the new component.
3. Click on the **Continue** button.

As for the regular content types, your new component should be configured with fields to be of use (see Adding and configuring fields), but it is already created and should be displayed in the list of components in the Content-Types Builder.