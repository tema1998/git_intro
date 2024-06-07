This is description of this pro
Add info about log_help.

echo "Команда checkout используется в Git, чтобы:" > branch_help.md
echo "* переключиться на произвольную существующую ветку (git checkout branch-name)" >> branch_help.md
echo "* создать новую ветку от текущей (git checkout -b new-branch-name)" >> branch_help.md
echo '- [Ветвление](./branch_help.md)' >> README.md


echo "Для слияния двух веток нужна команда merge" > merge_help.md
echo "- [Слияние веток](./merge_help.md)" >> README.md 