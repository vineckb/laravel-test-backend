## Server

- api
  - auth
  - register
  - user(auth required)
    - crud(list only user.role=$contratante)
  - $imovel(auth required)
    - create
    - update(only without contract actives)
    - delete(soft)
    - list: email, street, number, city, state, status
  - contract(auth required)
    - create
    - delete(soft)
