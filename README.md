# 萦晞如故｜气味名片测试

这是测试题独立网站包，打开 `index.html` 即可本地预览。

## 部署建议

- Vercel 新建一个独立项目，上传本文件夹。
- 建议绑定子域名：`test.yingxishengxiang.com` 或 `quiz.yingxishengxiang.com`。
- 这个包不包含艺术征稿、线上展厅、投稿、评审等入口，用户会把它理解为一个单纯的测试题网站。
- 如果后续要收集测试结果，建议新增 Supabase 表 `test_results`，不要继续依赖 Netlify Form。
