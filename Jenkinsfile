node
{
    if(env.TAG_NAME != null) //Buildtag
    {
        println "Build application from the tag ${env.TAG_NAME}"
    }
    else
    {
        println "Build from the branch"
    }
    if(env.TAG_NAME == 'release-2.0')
    {
        println "Build application from ${env.TAG_NAME}"
    }
}