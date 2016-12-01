1. Create new framework project add ui target

2. Manage schemes --> check shared on framework schema

3. carthage build --no-skip-current --platform ios

4. carthage archive TargetName

5. open zip. Navigate to iOS framework. Zip it

6. Github new release, drop new framework zip. publish
