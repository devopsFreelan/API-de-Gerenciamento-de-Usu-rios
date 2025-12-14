# API-de-Gerenciamento-de-Usu-rios
Backend desenvolvido em Spring Boot  CRUD completo com autenticação JWT  Integração com PostgreSQL



src/main/java/com/seuprojeto/api
│
├── controller
│   ├── AuthController.java
│   └── UsuarioController.java
│
├── service
│   ├── AuthService.java
│   └── UsuarioService.java
│
├── repository
│   └── UsuarioRepository.java
│
├── model
│   └── Usuario.java
│
├── dto
│   ├── LoginDTO.java
│   ├── UsuarioDTO.java
│   └── TokenDTO.java
│
├── security
│   ├── JwtAuthenticationFilter.java
│   ├── JwtTokenProvider.java
│   └── SecurityConfig.java
│
├── exception
│   ├── GlobalExceptionHandler.java
│   └── ResourceNotFoundException.java
│
├── config
│   └── DatabaseConfig.java (opcional)
│
└── ApiApplication.java
