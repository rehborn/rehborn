[![GPG-Badge]](https://rehborn.dev/public.asc)
[![SSH-Badge]](https://rehborn.dev/ssh.pub)

<div align="center">

[![](https://rehborn.dev/social-card-1280x640.png)](https://rehborn.dev)

[![](https://docs.rehborn.dev/assets/canary-cd.png)](https://docs.rehborn.dev)
[canary-cd](https://github.com/rehborn/canary-cd) &middot; 
[canary-cli](https://github.com/rehborn/canary-cli) &middot; 
[canary-deploy](https://github.com/rehborn/canary-deploy) &middot; 
[Documentation](http://docs.rehborn.dev) &middot; 
[Roadmap](https://github.com/users/rehborn/projects/4)

&nbsp;

<a href="https://rehborn.dev"><img src="https://cdn.rehborn.org/images/rehborn-dev-penguin.png" height="30px" /></a>
<a href="https://github.com/rehborn/canary-cd"><img src="https://docs.rehborn.dev/assets/canary-birb.png" height="30px" /></a>

</div>


[GPG-Badge]:
https://img.shields.io/badge/GPG-_?style=flat-square&labelColor=343434&color=0078ff&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjxzdmcKICAgdmlld0JveD0iMCAwIDUxMiA1MTIiCiAgIHZlcnNpb249IjEuMSIKICAgaWQ9InN2ZzEiCiAgIHNvZGlwb2RpOmRvY25hbWU9ImtleS1zb2xpZDIuc3ZnIgogICBpbmtzY2FwZTp2ZXJzaW9uPSIxLjQgKDE6MS40KzIwMjQxMDE2MTM1MStlN2MzZmViMTAwKSIKICAgeG1sbnM6aW5rc2NhcGU9Imh0dHA6Ly93d3cuaW5rc2NhcGUub3JnL25hbWVzcGFjZXMvaW5rc2NhcGUiCiAgIHhtbG5zOnNvZGlwb2RpPSJodHRwOi8vc29kaXBvZGkuc291cmNlZm9yZ2UubmV0L0RURC9zb2RpcG9kaS0wLmR0ZCIKICAgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIgogICB4bWxuczpzdmc9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZGVmcwogICAgIGlkPSJkZWZzMSIgLz4KICA8c29kaXBvZGk6bmFtZWR2aWV3CiAgICAgaWQ9Im5hbWVkdmlldzEiCiAgICAgcGFnZWNvbG9yPSIjZmZmZmZmIgogICAgIGJvcmRlcmNvbG9yPSIjNjY2NjY2IgogICAgIGJvcmRlcm9wYWNpdHk9IjEuMCIKICAgICBpbmtzY2FwZTpzaG93cGFnZXNoYWRvdz0iMiIKICAgICBpbmtzY2FwZTpwYWdlb3BhY2l0eT0iMC4wIgogICAgIGlua3NjYXBlOnBhZ2VjaGVja2VyYm9hcmQ9IjAiCiAgICAgaW5rc2NhcGU6ZGVza2NvbG9yPSIjZDFkMWQxIgogICAgIGlua3NjYXBlOnpvb209IjAuMjI2Mjc0MTciCiAgICAgaW5rc2NhcGU6Y3g9IjEwODcuMTc2NyIKICAgICBpbmtzY2FwZTpjeT0iODgxLjY3Mzc3IgogICAgIGlua3NjYXBlOndpbmRvdy13aWR0aD0iMTc3MCIKICAgICBpbmtzY2FwZTp3aW5kb3ctaGVpZ2h0PSIxMTcyIgogICAgIGlua3NjYXBlOndpbmRvdy14PSIxNTAiCiAgICAgaW5rc2NhcGU6d2luZG93LXk9IjI4IgogICAgIGlua3NjYXBlOndpbmRvdy1tYXhpbWl6ZWQ9IjAiCiAgICAgaW5rc2NhcGU6Y3VycmVudC1sYXllcj0ic3ZnMSIgLz4KICA8IS0tIUZvbnQgQXdlc29tZSBGcmVlIDYuNy4yIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlL2ZyZWUgQ29weXJpZ2h0IDIwMjUgRm9udGljb25zLCBJbmMuLS0+CiAgPHBhdGgKICAgICBkPSJNMzM2IDM1MmM5Ny4yIDAgMTc2LTc4LjggMTc2LTE3NlM0MzMuMiAwIDMzNiAwUzE2MCA3OC44IDE2MCAxNzZjMCAxOC43IDIuOSAzNi44IDguMyA1My43TDcgMzkxYy00LjUgNC41LTcgMTAuNi03IDE3bDAgODBjMCAxMy4zIDEwLjcgMjQgMjQgMjRsODAgMGMxMy4zIDAgMjQtMTAuNyAyNC0yNGwwLTQwIDQwIDBjMTMuMyAwIDI0LTEwLjcgMjQtMjRsMC00MCA0MCAwYzYuNCAwIDEyLjUtMi41IDE3LTdsMzMuMy0zMy4zYzE2LjkgNS40IDM1IDguMyA1My43IDguM3pNMzc2IDk2YTQwIDQwIDAgMSAxIDAgODAgNDAgNDAgMCAxIDEgMC04MHoiCiAgICAgaWQ9InBhdGgxIgogICAgIHN0eWxlPSJmaWxsOiNmZmZmZmYiIC8+Cjwvc3ZnPgo=

[SSH-Badge]:
https://img.shields.io/badge/SSH-_?style=flat-square&labelColor=343434&color=0078ff&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjxzdmcKICAgdmlld0JveD0iMCAwIDUxMiA1MTIiCiAgIHZlcnNpb249IjEuMSIKICAgaWQ9InN2ZzEiCiAgIHNvZGlwb2RpOmRvY25hbWU9ImtleS1zb2xpZDIuc3ZnIgogICBpbmtzY2FwZTp2ZXJzaW9uPSIxLjQgKDE6MS40KzIwMjQxMDE2MTM1MStlN2MzZmViMTAwKSIKICAgeG1sbnM6aW5rc2NhcGU9Imh0dHA6Ly93d3cuaW5rc2NhcGUub3JnL25hbWVzcGFjZXMvaW5rc2NhcGUiCiAgIHhtbG5zOnNvZGlwb2RpPSJodHRwOi8vc29kaXBvZGkuc291cmNlZm9yZ2UubmV0L0RURC9zb2RpcG9kaS0wLmR0ZCIKICAgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIgogICB4bWxuczpzdmc9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZGVmcwogICAgIGlkPSJkZWZzMSIgLz4KICA8c29kaXBvZGk6bmFtZWR2aWV3CiAgICAgaWQ9Im5hbWVkdmlldzEiCiAgICAgcGFnZWNvbG9yPSIjZmZmZmZmIgogICAgIGJvcmRlcmNvbG9yPSIjNjY2NjY2IgogICAgIGJvcmRlcm9wYWNpdHk9IjEuMCIKICAgICBpbmtzY2FwZTpzaG93cGFnZXNoYWRvdz0iMiIKICAgICBpbmtzY2FwZTpwYWdlb3BhY2l0eT0iMC4wIgogICAgIGlua3NjYXBlOnBhZ2VjaGVja2VyYm9hcmQ9IjAiCiAgICAgaW5rc2NhcGU6ZGVza2NvbG9yPSIjZDFkMWQxIgogICAgIGlua3NjYXBlOnpvb209IjAuMjI2Mjc0MTciCiAgICAgaW5rc2NhcGU6Y3g9IjEwODcuMTc2NyIKICAgICBpbmtzY2FwZTpjeT0iODgxLjY3Mzc3IgogICAgIGlua3NjYXBlOndpbmRvdy13aWR0aD0iMTc3MCIKICAgICBpbmtzY2FwZTp3aW5kb3ctaGVpZ2h0PSIxMTcyIgogICAgIGlua3NjYXBlOndpbmRvdy14PSIxNTAiCiAgICAgaW5rc2NhcGU6d2luZG93LXk9IjI4IgogICAgIGlua3NjYXBlOndpbmRvdy1tYXhpbWl6ZWQ9IjAiCiAgICAgaW5rc2NhcGU6Y3VycmVudC1sYXllcj0ic3ZnMSIgLz4KICA8IS0tIUZvbnQgQXdlc29tZSBGcmVlIDYuNy4yIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlL2ZyZWUgQ29weXJpZ2h0IDIwMjUgRm9udGljb25zLCBJbmMuLS0+CiAgPHBhdGgKICAgICBkPSJNMzM2IDM1MmM5Ny4yIDAgMTc2LTc4LjggMTc2LTE3NlM0MzMuMiAwIDMzNiAwUzE2MCA3OC44IDE2MCAxNzZjMCAxOC43IDIuOSAzNi44IDguMyA1My43TDcgMzkxYy00LjUgNC41LTcgMTAuNi03IDE3bDAgODBjMCAxMy4zIDEwLjcgMjQgMjQgMjRsODAgMGMxMy4zIDAgMjQtMTAuNyAyNC0yNGwwLTQwIDQwIDBjMTMuMyAwIDI0LTEwLjcgMjQtMjRsMC00MCA0MCAwYzYuNCAwIDEyLjUtMi41IDE3LTdsMzMuMy0zMy4zYzE2LjkgNS40IDM1IDguMyA1My43IDguM3pNMzc2IDk2YTQwIDQwIDAgMSAxIDAgODAgNDAgNDAgMCAxIDEgMC04MHoiCiAgICAgaWQ9InBhdGgxIgogICAgIHN0eWxlPSJmaWxsOiNmZmZmZmYiIC8+Cjwvc3ZnPgo=
