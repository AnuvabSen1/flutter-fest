# flutter-fest

This App uses [`Weather API`](https://www.weatherapi.com/) and `PageView` to display two pages
  1. Landing page for displaying weather of user's current location via GPS    
  2. Next page for custom locations:
      - Uses `ChangeNotifierProvider`to provide `addedLocations` to the Scaffold's AppBar's `IconButton` and Scaffold's `body`
      - Uses `SharedPreferences` to save the added locations even after the app is closed

## Thanks a lot for visting my project

