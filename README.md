# REPRO STEPS

## PNPM 5.5.11
```
rimraf node_modules
git clean -ffx
npm install -g pnpm@^5.5.11
pnpm install
tsc a.ts
```
&#x1F534; Compilation fails.

## PNPM 4.14.4
```
rimraf node_modules
git clean -ffx
npm install -g pnpm@^4.14.4
pnpm install
tsc a.ts
```
&#x1F534; Compilation fails.

## PNPM 3.4.1
```
rimraf node_modules
git clean -ffx
npm install -g pnpm@~3.4.1
pnpm install
tsc a.ts
```
&#x1F534; Compilation fails.

## YARN
```
rimraf node_modules
git clean -ffx
yarn install
tsc a.ts
```
&#128994; Compiles successfully.

## NPM
```
rimraf node_modules
git clean -ffx
npm install
tsc a.ts
```
&#128994; Compiles successfully.
