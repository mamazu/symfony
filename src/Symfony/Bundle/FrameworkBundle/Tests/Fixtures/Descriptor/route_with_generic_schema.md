some_route_with_host
--------------------

- Path: /some-route
- Path Regex: #PATH_REGEX#
- Host: symfony.com
- Host Regex: #HOST_REGEX#
- Scheme: ANY
- Method: ANY
- Class: Symfony\Bundle\FrameworkBundle\Tests\Console\Descriptor\RouteStub
- Defaults:
    - `_controller`: array (0 => 'Symfony\\Bundle\\FrameworkBundle\\Controller\\RedirectController',1 => 'redirectAction',)
- Requirements: NO CUSTOM
- Options:
    - `compiler_class`: Symfony\Component\Routing\RouteCompiler
