## Release Checklist

### Update main branch, tag and publish
- [ ] git checkout main
- [ ] npm install
- [ ] npm run test
- [ ] npm run txpull
- [ ] git add . && git commit -m 'npm run txpull'
- [ ] Update `CHANGELOG.md`
- [ ] Update version number in `package.json`
- [ ] npm run dist
- [ ] git add . && git commit -m 'vA.B.C'
- [ ] git tag vA.B.C
- [ ] git push origin main vA.B.C
- [ ] npm publish

Open https://github.com/ideditor/imagery-index/tags
Click "Add Release Notes" and link to the CHANGELOG
