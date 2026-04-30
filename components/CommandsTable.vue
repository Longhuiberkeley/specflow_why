<template>
  <div class="text-[0.65rem] leading-tight">
    <table>
      <thead>
        <tr>
          <th>#</th>
          <th>Slash Command</th>
          <th>When to Use</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td><code>/specflow-init</code></td>
          <td>Starting a new project; installing skills, packs, CI</td>
        </tr>
        <tr>
          <td>2</td>
          <td><code>/specflow-discover</code></td>
          <td>Capturing a new requirement through conversation</td>
        </tr>
        <tr>
          <td>3</td>
          <td><code>/specflow-plan</code></td>
          <td>Breaking approved REQs into architecture + stories</td>
        </tr>
        <tr>
          <td>4</td>
          <td><code>/specflow-execute</code></td>
          <td>Implementing approved stories with test generation</td>
        </tr>
        <tr>
          <td>5</td>
          <td><code>/specflow-artifact-review</code></td>
          <td>Quality review of one or more specific artifacts</td>
        </tr>
        <tr>
          <td>6</td>
          <td><code>/specflow-change-impact-review</code></td>
          <td>Blast-radius review of recent commits/PRs</td>
        </tr>
        <tr>
          <td>7</td>
          <td><code>/specflow-audit</code></td>
          <td>Periodic full-project health check</td>
        </tr>
        <tr>
          <td>8</td>
          <td><code>/specflow-ship</code></td>
          <td>Cutting a release: baseline + change records + quick audit</td>
        </tr>
        <tr>
          <td>9</td>
          <td><code>/specflow-pack-author</code></td>
          <td>Authoring a standards compliance pack</td>
        </tr>
        <tr>
          <td>10</td>
          <td><code>/specflow-adapter</code></td>
          <td>Managing CI, exchange formats (ReqIF), standards, team RBAC</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style scoped>
td, th { padding: 0.15rem 0.5rem !important; }
</style>