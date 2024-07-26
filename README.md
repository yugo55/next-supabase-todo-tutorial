# Next.js + SupabaseでToDoアプリチュートリアル
## 備忘録
### 手順
1. Supabaseでプロジェクト作成。
2. supabaseテンプレートを使用してnext.jsプロジェクト作成し、.envファイルで環境変数設定。
3. Supabaseでテーブル作成。
4. SupabaseのSQL Editerで更新用トリガー作成。
5. `utils/supabase/supabase.ts`、`types/supabasetype.ts`など必要ファイルの作成。
6. `npx supabase gen types typescript --project-id "$PROJECT_ID" --schema public > types/supabasetype.ts`でDBと連携。
7. `utils/supabase/supabase.ts`を記述。
8. 各ファイルを記述。

## 参考サイト
https://note.com/libproc/n/n53c198d347d1
