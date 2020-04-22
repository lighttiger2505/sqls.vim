# sqls.vim

Vim plugin for [sqls](https://github.com/lighttiger2505/sqls)

## install

For vim-plug

```vim
Plug 'lighttiger2505/sqls.vim'
Plug 'prabirshrestha/vim-lsp'
Plug 'prabirshrestha/async.vim'
Plug 'junegunn/fzf', { 'do': { -> fzf#install() } }
```

### depends

- [sqls](https://github.com/lighttiger2505/sqls)
- [vim-lsp](https://github.com/prabirshrestha/vim-lsp)
    - [async.vim](https://github.com/prabirshrestha/async.vim)
- [fzf](https://github.com/junegunn/fzf)

## Feature

![sqls.vim demo](./imgs/sqls_vim_demo.gif)

| Commands                                            | Plug Mappings                  | Description                                                                  |
|-----------------------------------------------------|--------------------------------|------------------------------------------------------------------------------|
| SqlsExecuteQuery                                    | <plug>(sqls-execute-query)     | execute query of the current buffer adn show query result to preview buffer. |
| SqlsShowConnections                                 | <plug>(sqls-show-connections)  | show database connection to preview buffer.                                  |
| SqlsShowDatabases                                   | <plug>(sqls-show-databases)    | show database to preview buffer.                                             |
| SqlsSwitchDatabase                                  | <plug>(sqls-switch-database)   | select and swith database. Requirement fzf.                                  |
| SqlsSwitchDatabase `<DB Name>`                      | -                              | swith database.                                                              |
| SqlsSwitchSqlsSwitchConnection                      | <plug>(sqls-switch-connection) | select and swith database connection. Requirement fzf.                       |
| SqlsSwitchSqlsSwitchConnection `<Connection Index>` | -                              | swith database connection.                                                   |
