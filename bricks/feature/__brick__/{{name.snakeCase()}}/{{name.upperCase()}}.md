# {{name.titleCase()}}

## Description

Jira : [[TICKET-ID]]([TICKET-URL]) \
Confluence : [doc]([CONFLUENCE-URL])

> {{description}}

---

## File architecture

* [services/](services/)
  * [{{name.pascalCase()}}Service](services/{{name.snakeCase()}}_service.dart)
  * [Ws{{name.pascalCase()}}Model](services/ws_{{name.snakeCase()}}_model.dart)

* [states/](states/)
  * [{{name.pascalCase()}}State](states/{{name.snakeCase()}}_state.dart)
  * [{{name.pascalCase()}}Cubit](states/{{name.snakeCase()}}_cubit.dart)

* [presentation/](presentation/)
  * [Ui{{name.pascalCase()}}Model](presentation/ui_{{name.snakeCase()}}_model.dart)
  * [{{name.pascalCase()}}](presentation/{{name.snakeCase()}}.dart)
