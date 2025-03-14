run tests: `pytest`
increment version
update README.md
update changelog.md
git add .
git tag v0.1.5
git push origin v0.1.5
rm -rf dist/ build/ src/eg4_inverter_api.egg-info/
python -m build
twine upload dist/*


