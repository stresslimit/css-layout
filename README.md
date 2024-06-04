# CSS Layout

Simplest flexbox-based, human-readable css layout classes.
Requires `var(--unit)` to be set upstream in your project.

```
  container     1000px
  container-md  800px
  container-sm  600px

  -----------------------------------------
  row

  |        half       |        half       |

  |   third   |    third    |    third    |

  |   third   |        two-thirds         |

  | quarter | quarter | quarter | quarter |

  | fifth | fifth | fifth | fifth | fifth | 

  -----------------------------------------
```

`.row` kicks in at 768px wide. For columns on phones, use `.row-xs`


### Helpers

`grow | shrink`

`valign-top`

`distribute`
