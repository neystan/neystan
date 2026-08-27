# Contribution Snake

自动生成 GitHub Contribution Snake 动画。

生成后的文件位于 `output` 分支：

```markdown
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/neystan/Contribution_Snake/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)"
          srcset="https://raw.githubusercontent.com/neystan/Contribution_Snake/output/github-snake.svg">
  <img alt="GitHub contribution snake"
       src="https://raw.githubusercontent.com/neystan/Contribution_Snake/output/github-snake.svg">
</picture>
```

工作流每天自动运行一次，也可以在 GitHub Actions 页面手动触发。
