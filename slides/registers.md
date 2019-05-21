## Yank, Put and Delete

| vim    | normal term | command
| ---    | ---         | ---
| yank   | copy        | y
| put    | paste       | p
| delete | cut         | d

--

## Registers

Registers can be named from a-z with some special characters reserved for special use cases

<dl>
  <dt>"d</dt>
  <dd>save into or put from register (d)</dd>
  <dt>"D</dt>
  <dd>append to register (d)</dd>
  <dt>:reg</dt>
  <dd>see what is currently in the registers</dd>
</dl>

--

## Special Registers

| register | use |
| ---      | --- |
| +        | accesses the system clipboard |
| 0 | the text from the most recent yank command |
| 1-9 | the text from the most recent delete command is stored in one with the previous being shifted to 2 and so forth up to 9 |
| . | the last text entered in insert mode |
| : | the text of the most recent command-line command
| % | the text of the current filename
