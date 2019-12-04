# ktor-API-examples

### Ejemplos con KTOR para la creación de un API REST


#### [01 Basic API | CRUD](https://github.com/vicboma1/ktor-API-examples/tree/master/01-basic-api) 
```
    Exposición de una API básica con los elementos operacionales del CRUD
    Operaciones: [ get, put, post, delete]
    PipelineContext semántico
    Bloque SafetyAsync en los elementos del route
```
![](https://github.com/vicboma1/ktor-API-examples/blob/master/00-assets/01-basic-api.png)


#### 02 Rich API | CRUD
```
    Refactors en el routing anclando el end-point base
    Refactors en el route sin rutas, solo parámetros de entrada
    Exposición de una API enriquecida con los elementos operacionales del CRUD
    Operaciones: [ get, put, post, delete, getAll, deleteAll]
    PipelineContext semántico
    Bloque SafetyAsync en los elementos del route
```
![](https://github.com/vicboma1/ktor-API-examples/blob/master/00-assets/02-rich-api.png)


#### 03 Locations API | type-safe Routing
```
    Modelos tipados con anotaciones @Locations (refactor friendly)
    Tipado estático para el acceso de diferentes parametros en el route
    Refactors en el routing sin el end-point
    Refactors en el route sin rutas
    Exposición de una API enriquecida con los elementos operacionales del CRUD tipados
    Operaciones: [ get<T>, put<T>, post<T>, delete<T>, getAll<T>, deleteAll<T> ]
    PipelineContext semántico
    Bloque SafetyAsync en los elementos del route
```
![](https://github.com/vicboma1/ktor-API-examples/blob/master/00-assets/03-location-api.png)


#### 04 Async API | withContext 
```
    Exposición de una API enriquecida con los elementos operacionales del CRUD - number
    Operaciones: [ get, getAll, add, postMinor, postMajor, postEquals, delete, deleteAll ]
    Bloque SafetyAsyncWithContext en los elementos del route (no optimizado, es global a la operación)
    Retrocompatibilidad con proyecto [ 03 Locations API | type-safe Routing ]
```
![](https://github.com/vicboma1/ktor-API-examples/blob/master/00-assets/04-async-api.png)

#### 05 Flow API |  
```
    Exposición de una API enriquecida con elementos operacionales reactivos y diferentes block-body
    Operaciones: [ getFlow, getFlowBlock, getFlowContext, getFlowOdd, getFlowBlockOdd, getFlowContextOdd,getFlowEven, getFlowBlockEven, getFlowContextEven ]
    Refactor en el routing con un solo entryPoint 
    Retrocompatibilidad con proyecto [ 04 Async API | withContext ]
```
![](https://github.com/vicboma1/ktor-API-examples/blob/master/00-assets/04-async-api.png)

### Referencias 

    *  [Documentación oficial](https://ktor.io/)
    *  [Mobile Backends with Kotlin and Google Cloud (Google I/O'19)](https://youtu.be/zjWOMBdPbsI)
    *  [GOTO 2019 • Server-side Kotlin with Coroutines • Roman Elizarov](https://www.youtube.com/watch?v=hQrFfwT1IMo=
    *  [Asynchronous-flow](https://github.com/Kotlin/kotlinx.coroutines/blob/7f0da424ed98e3a30e0a7ca2daff33f9a9cdbf0c/docs/flow.md#asynchronous-flow)
    *  [LiveData with Coroutines and Flow (Android Dev Summit '19)](https://www.youtube.com/watch?v=B8ppnjGPAGE)
    *  [Repo: Getting Started Kotlin](https://github.com/vicboma1/GettingStartedKotlin)    
    *  [Repo: Problems Kotlin](https://github.com/vicboma1/Kotlin-Examples-Problems/blob/master/README.md)    
    *  [Repo: GameBoy Emulator Enviroment](https://github.com/vicboma1/GameBoyEmulatorEnvironment)    
    *  [Repo: Kotlin Mobile](https://github.com/vicboma1/KotlinMobilePoC_MasterUV2018)    
    *  [Repo: Kotlin JavaScript](https://github.com/vicboma1/kotlinJavaScript)   
    *  [Repo: Kotlin Native-iOS](https://github.com/vicboma1/Kotlin-Native-iOS-ConsoleAsync)   
    *  [Repo: Kotlin Koans Examples](https://github.com/vicboma1/Kotlin-Koans)   