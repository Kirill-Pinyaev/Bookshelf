# BookShelf

Учебный REST-сервис на Go (chi + net/http) для управления книгами. Реализует CRUD, простую валидацию, middleware-цепочку (RequestID → Logging → Recoverer → Timeout) и **graceful shutdown**. По умолчанию использует потокобезопасное **in-memory** хранилище.

