# Questions

* Why `assert.equal( 12, '12', 'numbers are coerced into strings with == ');` fails but `assert.equal( '12', 12, 'numbers are coerced into strings with == ');`passes? `12 == '12' , '12' == 12` both are true. Does only second parameter get coerced?

* isApproximately question.