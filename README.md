# The Open Podcast Standard

The Open Podcast Standard provides an open space for extending the RSS de-facto standard for podcasts.

## Feedback

The feedback extensions aim at providing a feedback channel back to the podcast hosts

### Thumbs Feedback

This extensions provides a simple thumbs up/down vote mechanism to listeners aiming at giving quick feedback that is immediatly sent back to the podcast hosts. It is not bound to any service or tool and therefore, can be easily integrated to any feedback service.

Proposal:

```xml
<ops:feedback>
  <ops:thumbsfeedback>
    <ops:up-endpoint>https://someurl</ops:up-endpoint>
    <ops:down-endpoint>https://someurl</ops:down-endpoint>
  </ops:thumbsfeedback>
</ops:feedback>
```
