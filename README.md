#A simple sysout to slf4j transformer

This application tries to convert a System using System.out and System.err for debug message into a system which uses the slf4j framework.
All standard outs are transformed to logging statements of level info. All error outputs are transformed to logging statements of level error.
printStackTrace statements are transformed to log statements of Level warning.
