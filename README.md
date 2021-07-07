# Nested_Navigation_Flow

1-Prepare for navigation
2-Display an app bar for the setup flow
3-Generate nested routes
4-Interactive example

Consider an Internet of Things (IoT) setup flow for a wireless light bulb that you control with your app. This setup flow consists of 4 pages: find nearby bulbs, select the bulb that you want to add, add the bulb, and then complete the setup. You could orchestrate this behavior from your top-level Navigator widget. However, it makes more sense to define a second, nested Navigator widget within your SetupFlow widget, and let the nested Navigator take ownership over the 4 pages in the setup flow. This delegation of navigation facilitates greater local control, which is generally preferable when developing software.

![Download Button](https://flutter.dev/assets/cookbook/effects/NestedNavigator-f0b13e90b5a6b2c32c0e8c158302bfbc19cd6bd681468f1ba0303a68e187da40.gif)