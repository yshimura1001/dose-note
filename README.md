# 服薬管理アプリ 服薬ノート(dose-note)

## 技術スタック
### 採用したもの
- 共通
  - プログラミング言語：TypeScript 5.9.3
  - パッケージマネージャ―：pnpm 10.25.0
  - パッケージマネージャー統合ツール：ni 28.0.0
  - ビルドツール：Vite 7.2.7
- フロントエンド・モバイルアプリ共通
  - UIライブラリ：SolidJS 1.9.10
  - スタイリング：TailwindCSS 4.1.18
  - ルーティング：TanStack Router 1.141.2
  - バリデーション：Zod 3.25.76
- モバイルアプリ
- バックエンド
- 開発ツール
  - ランタイム：Node 24.12.0
  - リンター・フォーマッター：Biome 2.3.8
  - モノレポ管理ツール：Turborepo 2.6.3
### 導入予定のもの
- 共通
  - 認証ライブラリ：BetterAuth.js
  - テストツール：Vitest
  - インフラ：Cloudflare Workers
- フロントエンド・モバイルアプリ共通
  - UIコンポーネントキット：Shadcn/ui
- モバイルアプリ
  - UIキット：Ionic
  - モバイルアプリ化ツール：Capacitor
- バックエンド
  - フレームワーク：Hono
  - ORM：Drizzle
### 検討中のもの
- フロントエンド・モバイルアプリ共通
  - データ取得・状態管理ライブラリ：TanStack Query
  - フォームライブラリ：TanStack Form