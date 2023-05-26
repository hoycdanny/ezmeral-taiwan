# Logging

日誌記錄是指捕獲、收集和存儲運行在 Kubernetes 集群中的應用程序、容器和 Kubernetes 組件產生的日誌數據的過程。日誌記錄對於集群內的應用程序和基礎設施的監控和故障排除至關重要。平台整合Fluent Bit 用於 Pod 日誌文件和快照執行日誌記錄。

### 點選Data Engineering > Data Sources > Browse即可瀏覽日誌

![](<../../.gitbook/assets/image (4).png>)

#### apps/&#x20;

包含平台元件和應用程式日誌。&#x20;

#### System/&#x20;

包含系統節點服務日誌。

![](<../../.gitbook/assets/截圖 2023-05-26 下午1.39.52.png>)

### 應用程式面的日誌

![](<../../.gitbook/assets/image (8).png>)

#### shared/app-core/&#x20;

存放核心應用程式的日誌&#x20;

#### shared/app-user/&#x20;

用戶啟動的Pod 例如 notebooks, Inference Jobs, Spark Jobs。&#x20;

#### shared/platform/&#x20;

平台的 Pod日誌。



### 日誌快照功能。

可將平台日誌快照根據時間快照，加速支援團隊故障排除。

#### /shared/snapshots

![](<../../.gitbook/assets/image (5).png>)



