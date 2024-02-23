
# Usage Notes

## WKE_im
### 使用在一開始初始使用，會一同import相關元件供整個畫面使用

- `!WKE_im_component`
- `!WKE_im_container`
- `!WKE_im_action_get/set`
- `!WKE_im_action_start/suc/err`
- `!WKE_im_reducer_get/set`
- `!WKE_im_reducer_start/suc/err`
- `!WKE_im_saga`

## Action
### 分為兩種型態：

- `!WKE_action_get/set`
僅包含 get 與 set 兩項的簡單操作，success 與 error 均在 set_action 裡面操作

- `!WKE_action_start/suc/err`
包含 start、success 和 error，成功失敗均可分別操作

- `!WKE_action_onchange`
提供 onchange 的單一項操作，沒有 set 或 success 或 error 的使用

## Reducer
### 配合 action 亦分成 get/set，與 start/success/error 兩種型態：

- `!WKE_reducer_get/set`
- `!WKE_reducer_start/suc/err`

## Saga
- `!WKE_saga`


# Version note 

1.0.0
Initial release of 2023/11/20

1.0.1
release of 2023/11/21


**Enjoy!**