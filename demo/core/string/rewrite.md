## String#rewrite

    require 'facets/string/rewrite'

    s = "HELLO TOMMY!"
    rules = [[ /TOMMY/, 'MAN' ]]
    r = s.rewrite(rules)
    r.assert == "HELLO MAN!"

