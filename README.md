<h1 align="center">Miruro App</h1>

<p align="center">  
This project allows users to watch their favorite anime in android tv and mobile. 
</p>

<h1 align="center"> Powered by Anilist API and Miruro.TV</h1>

## App Support
 - Android TV, Mobile , Tablets and Flips (Please use the specific .apk file to base on your needs)
 - Android Version 8 +

## App Preview
Dashboard 
 - Carousel of the latest and trending anime right now
 - List Selection of Anime from Latest - Top Rating - Popular
 - Readable Anime Information
   
![image](https://github.com/user-attachments/assets/44f25f60-93f4-4a9f-bf4d-e86da63179ff)

![image](https://github.com/user-attachments/assets/ca51e60f-df94-4010-ab10-c222e74f72b2)

Search
 - On screen keyboard
 - Easy to Select Filters

![image](https://github.com/user-attachments/assets/e178e1aa-da4e-4b94-9fef-b79dac6399f7)

![image](https://github.com/user-attachments/assets/5070b09a-0177-4162-b705-9ef742a1bac6)

Trending 
 - List of anime this year according to there season

![image](https://github.com/user-attachments/assets/91b923b4-ccb8-402d-9c95-34c70c395bab)

History
 - Local save of your progress

![image](https://github.com/user-attachments/assets/ad8bbffe-86be-4d17-bfa4-a598aa955cb3)

Detail
 - View Additional Information of the anime

![image](https://github.com/user-attachments/assets/4a39c85a-5ed1-4c9f-832e-ecb90fa6829d)

Player
 - Fullscreen display of the anime
 - Switch from different providers
 - Support different subtitles
 - Also seamless switching to different episodes

![image](https://github.com/user-attachments/assets/c56a77a5-11dc-46c7-8d85-3741d8f3be3a)

![image](https://github.com/user-attachments/assets/4aeed9b4-9c91-44f9-98d0-3f2a60aad9c4)

![image](https://github.com/user-attachments/assets/c4181cf2-acc7-4a6b-90e5-74b4ef729e9e)

![image](https://github.com/user-attachments/assets/0c44f905-5177-4544-8f40-e29820bea7f9)



## Tech stack & Open-source libraries
- Minimum SDK level 26.
- [Kotlin](https://kotlinlang.org/) based, utilizing [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous operations.
- Jetpack Libraries:
  - Jetpack Compose: Android’s modern toolkit for declarative UI development.
  - Lifecycle: Observes Android lifecycles and manages UI states upon lifecycle changes.
  - ViewModel: Manages UI-related data and is lifecycle-aware, ensuring data survival through configuration changes.
  - Room: Constructs a database with an SQLite abstraction layer for seamless database access.
  - [Hilt](https://dagger.dev/hilt/): Facilitates dependency injection.
- Architecture:
  - MVVM Architecture (View - ViewModel - Model): Facilitates separation of concerns and promotes maintainability.
  - Repository Pattern: Acts as a mediator between different data sources and the application's business logic.
- [Kotlin Serialization](https://github.com/Kotlin/kotlinx.serialization): Kotlin multiplatform / multi-format reflectionless serialization.
- [ksp](https://github.com/google/ksp): Kotlin Symbol Processing API for code generation and analysis.
- [Coil](https://coil-kt.github.io/coil/) Jetpack compose image loading library.
- [Constraint Layout] For complex ui designs.
- GrahpQL using Apollo Kotlin
- Anilist Api for Anime List



