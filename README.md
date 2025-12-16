# 服薬管理アプリ 服薬ノート(dose-note)

## 技術スタック
### 採用したもの
- フロントエンド(apps/web)
  - UIライブラリ：SolidJS 1.9.10
  - スタイリング：TailwindCSS 4.1.18
  - ルーティング：TanStack Router 1.141.2
- モバイルアプリ(apps/mobile)
  - UIライブラリ：Vue 8.7.13
  - スタイリング・UIキット：Ionic 8.7.13
  - ルーティング：Ionic Vue Router 8.7.13
  - モバイルアプリ化ツール：Capacitor 8.0.0
- バックエンド
- 開発ツール
  - プログラミング言語：TypeScript 5.9.3
  - ランタイム：Node 24.12.0
  - パッケージマネージャ―：pnpm 10.26.0
  - パッケージマネージャー統合ツール：ni 28.0.0
  - ビルドツール：Vite 7.2.7
  - モノレポ管理ツール：Turborepo 2.6.3
  - リンター・フォーマッター：Biome 2.3.8
  - バリデーション：Zod 3.25.76
### 導入予定のもの
- 共通
  - 認証ライブラリ：BetterAuth.js
  - テストツール：Vitest
  - インフラ：Cloudflare Workers
- フロントエンド・モバイルアプリ共通
  - UIコンポーネントキット：Shadcn/ui
- バックエンド
  - BaaS：Supabase
  - フレームワーク：Hono
  - ORM：Drizzle
### 検討中のもの
- フロントエンド・モバイルアプリ共通
  - データ取得・状態管理ライブラリ：TanStack Query
  - フォームライブラリ：TanStack Form