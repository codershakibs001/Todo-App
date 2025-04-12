# 🔥 Go Rest app

![](https://github.com/SinaSys/flutter_go_rest_app/blob/master/screenshots/go_rest.jpg?raw=true)

## 📂 Directory Structure (MVVM architecture version + GetX)
```
📂lib
│───main.dart  
│───di.dart  
│───📂common  
│   │───📂controller
│   │   └──base_controller.dart
│   │───📂repository
│   │   └──repository_helper.dart
│   │───📂network
│   │   │──api_helper.dart
│   │   │──api_result.dart
│   │   │──api_result.freezed.dart
│   │   │──dio_client.dart
│   │   │──dio_exception.dart
│   │   └──dio_interceptor.dart
│   │───📂widget
│   │   │──date_time_picker.dart
│   │   │──drop_down.dart
│   │   │──empty_widget.dart
│   │   │──popup_menu.dart
│   │   │──spinkit_indicator.dart
│   │   └──text_input.dart
│   └───📂dialog
│       │──create_dialog.dart
│       │──delete_dialog.dart
│       │──progress_dialog.dart
│       └──retry_dialog.dart
│───📂core
│   │──api_config.dart
│   │──app_asset.dart
│   │──app_extension.dart
│   │──app_string.dart
│   │──app_style.dart
│   └──app_theme.dart
│
│───📂data
│   │───📂api
│   │    │───📂comment
│   │    │   └──comment_api.dart
│   │    │───📂post
│   │    │   └──post_api.dart
│   │    │───📂todo
│   │    │   └──todo_api.dart
│   │    └───📂user
│   │        └──user_api.dart
│   │    
│   └───📂model 
│        │───📂comment
│        │   │──comment.dart
│        │   └──comment.g.dart
│        │───📂post
│        │   │──post.dart
│        │   └──post.g.dart
│        │───📂todo
│        │   │──todo.dart
│        │   └──todo.g.dart
│        └───📂user
│            │──user.dart
│            └──user.g.dart 
│    
│───📂repository
│    │───📂comment
│    │   └──comment_repository.dart
│    │───📂post
│    │   └──post_repository.dart
│    │───📂todo
│    │   └──todo_repository.dart
│    └───📂user
│        └──user_repository.dart
│
│───📂view
│    │───📂post
│    │   └──📂screen
│    │      │──create_post_screen.dart
│    │      │──post_detail_screen.dart
│    │      └──post_list_screen.dart
│    │    
│    │───📂todo
│    │   │──📂screen
│    │   │  └──todo_list_screen.dart
│    │   └──📂widget
│    │      │──circle_container.dart
│    │      └──todo_list_item.dart
│    │
│    └───📂user
│        │──📂screen
│        │  └──user_list_screen.dart
│        └──📂widget
│           └──status_container.dart
│     
└───📂viewmodel
         │───📂comment
         │   └──📂controller
         │      └──comment_controller.dart
         │───📂post
         │   └──📂controller
         │      └──post_controller.dart
         │───📂todo
         │   └──📂controller
         │      └──todo_controller.dart
         └───📂user
             └──📂controller
                └──user_controller.dart


```


