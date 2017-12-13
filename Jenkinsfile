node("linux") {
  stage("TEST") {
    echo new groovy.json.JsonBuilder(foo).toPrettyString(env)
    echo new groovy.json.JsonBuilder(foo).toPrettyString(scm)
  }
}
