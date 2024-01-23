# [Nuxt Argon Dashboard PRO](https://github.com/creativetimofficial/ct-nuxt-argon-dashboard-pro) [![version][version-badge]][CHANGELOG] [![license][license-badge]][LICENSE]


## Documentation
The documentation for the Nuxt Argon Dashboard is hosted at our [website](https://demos.creative-tim.com/nuxt-argon-dashboard-pro/documentation?ref=nadap-github-readme).


## File Structure
Within the download you'll find the following directories and files:

```
|-- nuxt-argon-dashboard-pro
    |-- App.vue
    |-- main.js
    |-- polyfills.js
    |-- assets
    |   |-- css
    |   |   |-- nucleo
    |   |-- sass
    |       |-- argon.scss
    |       |-- core
    |       |-- custom
    |-- components
    |   |-- Badge.vue
    |   |-- BaseAlert.vue
    |   |-- BaseButton.vue
    |   |-- BaseDropdown.vue
    |   |-- BaseHeader.vue
    |   |-- BasePagination.vue
    |   |-- BaseProgress.vue
    |   |-- BaseSwitch.vue
    |   |-- BaseTable.vue
    |   |-- CloseButton.vue
    |   |-- LoadingPanel.vue
    |   |-- Modal.vue
    |   |-- NavbarToggleButton.vue
    |   |-- Slider.vue
    |   |-- index.js
    |   |-- Breadcrumb
    |   |   |-- Breadcrumb.vue
    |   |   |-- BreadcrumbItem.vue
    |   |   |-- RouteBreadcrumb.vue
    |   |-- Cards
    |   |   |-- Card.vue
    |   |   |-- StatsCard.vue
    |   |-- Charts
    |   |   |-- BarChart.js
    |   |   |-- DoughnutChart.js
    |   |   |-- LineChart.js
    |   |   |-- PieChart.js
    |   |   |-- config.js
    |   |   |-- globalOptionsMixin.js
    |   |   |-- optionHelpers.js
    |   |-- Collapse
    |   |   |-- Collapse.vue
    |   |   |-- CollapseItem.vue
    |   |-- Feed
    |   |   |-- Comment.vue
    |   |-- Inputs
    |   |   |-- BaseCheckbox.vue
    |   |   |-- BaseInput.vue
    |   |   |-- BaseRadio.vue
    |   |   |-- DropzoneFileUpload.vue
    |   |   |-- FileInput.vue
    |   |   |-- HtmlEditor.vue
    |   |   |-- IconCheckbox.vue
    |   |   |-- TagsInput.vue
    |   |-- Navbar
    |   |   |-- BaseNav.vue
    |   |   |-- NavbarToggleButton.vue
    |   |-- NotificationPlugin
    |   |   |-- Notification.vue
    |   |   |-- Notifications.vue
    |   |   |-- index.js
    |   |-- SidebarPlugin
    |   |   |-- SideBar.vue
    |   |   |-- SidebarItem.vue
    |   |   |-- index.js
    |   |-- Tabs
    |   |   |-- Tab.vue
    |   |   |-- Tabs.vue
    |   |-- Timeline
    |   |   |-- TimeLine.vue
    |   |   |-- TimeLineItem.vue
    |   |-- WorldMap
    |       |-- AsyncWorldMap.vue
    |       |-- WorldMap.vue
    |-- directives
    |   |-- click-ouside.js
    |-- plugins
    |   |-- dashboard-plugin.js
    |   |-- globalComponents.js
    |   |-- globalDirectives.js
    |-- routes
    |   |-- router.js
    |   |-- routes.js
    |   |-- starterRouter.js
    |-- util
    |   |-- throttle.js
    |-- views
        |-- Charts.vue
        |-- Widgets.vue
        |-- Calendar
        |   |-- Calendar.vue
        |-- Components
        |   |-- Buttons.vue
        |   |-- Cards.vue
        |   |-- GridSystem.vue
        |   |-- Icons.vue
        |   |-- Notifications.vue
        |   |-- Typography.vue
        |-- Dashboard
        |   |-- ActivityFeed.vue
        |   |-- AlternativeDashboard.vue
        |   |-- Dashboard.vue
        |   |-- LightTable.vue
        |   |-- PageVisitsTable.vue
        |   |-- ProgressTrackList.vue
        |   |-- SocialTrafficTable.vue
        |   |-- TaskList.vue
        |   |-- UserList.vue
        |-- Forms
        |   |-- FormComponents.vue
        |   |-- FormElements.vue
        |   |-- FormValidation.vue
        |   |-- FormValidation
        |       |-- BrowserDefaultsValidation.vue
        |       |-- CustomStylesValidation.vue
        |       |-- ServerSideValidation.vue
        |-- GeneralViews
        |   |-- NotFoundPage.vue
        |-- Layout
        |   |-- Content.vue
        |   |-- ContentFooter.vue
        |   |-- DashboardLayout.vue
        |   |-- DashboardNavbar.vue
        |-- Maps
        |   |-- API_KEY.js
        |   |-- GoogleMaps.vue
        |   |-- VectorMaps.vue
        |-- Pages
        |   |-- AuthLayout.vue
        |   |-- Home.vue
        |   |-- Lock.vue
        |   |-- Login.vue
        |   |-- Pricing.vue
        |   |-- Register.vue
        |   |-- TimeLinePage.vue
        |   |-- UserProfile.vue
        |   |-- UserProfile
        |       |-- EditProfileForm.vue
        |       |-- UserCard.vue
        |-- Starter
        |   |-- SampleFooter.vue
        |   |-- SampleLayout.vue
        |   |-- SampleNavbar.vue
        |   |-- SamplePage.vue
        |-- Tables
        |   |-- PaginatedTables.vue
        |   |-- RegularTables.vue
        |   |-- SortableTables.vue
        |   |-- projects.js
        |   |-- users.js
        |   |-- users2.js
        |   |-- PaginatedTables
        |   |   |-- clientPaginationMixin.js
        |   |-- RegularTables
        |       |-- CheckboxColoredTable.vue
        |       |-- CheckboxTable.vue
        |       |-- DarkTable.vue
        |       |-- InlineActionsTable.vue
        |       |-- LightTable.vue
        |       |-- StripedTable.vue
        |       |-- TranslucentTable.vue
        |-- Widgets
            |-- CalendarWidget.vue
            |-- CreditCard.vue
            |-- MembersCard.vue
            |-- PaypalCard.vue
            |-- ProgressTrackList.vue
            |-- StatsCards.vue
            |-- TaskList.vue
            |-- TimelineCard.vue
            |-- VectorMapCard.vue
            |-- VisaCard.vue

```


## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">
